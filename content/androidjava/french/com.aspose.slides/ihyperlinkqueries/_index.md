---
title: IHyperlinkQueries
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Fournit un accès facile aux hyperliens contenus.
type: docs
url: /fr/com.aspose.slides/ihyperlinkqueries/
---
```
public interface IHyperlinkQueries
```

Fournit un accès facile aux hyperliens contenus.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Supprime tous les hyperliens HyperlinkClick et HyperlinkMouseOver contenus (dans tous les sous-objets IHyperlinkContainer). |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul. Avec l’objet IHyperlinkContainer fourni, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l’interface IHyperlinkContainer.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. Avec l’objet IHyperlinkContainer fourni, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l’interface IHyperlinkContainer.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. Avec l’objet IHyperlinkContainer fourni, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l’interface IHyperlinkContainer.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Supprime tous les hyperliens HyperlinkClick et HyperlinkMouseOver contenus (dans tous les sous-objets IHyperlinkContainer).