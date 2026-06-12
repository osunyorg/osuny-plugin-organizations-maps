# osuny-plugin-organizations-maps

## Installation


### Installer le submodule

`git submodule add https://github.com/osunyorg/osuny-plugin-organizations-maps themes/osuny-plugin-organizations-maps`

### Appeler le plugin

Dans `config/_default/config.yaml` :

```
_merge: deep
theme: 
  - osuny
  - osuny-plugin-organizations-maps
```

Le paramètre `merge: deep` est essentiel pour le bon fonctionnement du site !