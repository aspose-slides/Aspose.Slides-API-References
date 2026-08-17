---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java Référence API
description: Fournit un accès facile aux hyperliens contenus.
type: docs
url: /fr/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Fournit un accès facile aux hyperliens contenus.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Obtient tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Obtient tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Obtient tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Supprime tous les hyperliens HyperlinkClick et HyperlinkMouseOver contenus (dans tous les sous-objets IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Obtient tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul. Avec l'objet IHyperlinkContainer donné, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l'interface IHyperlinkContainer.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Obtient tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. Avec l'objet IHyperlinkContainer donné, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l'interface IHyperlinkContainer.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Obtient tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. Avec l'objet IHyperlinkContainer donné, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l'interface IHyperlinkContainer.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Supprime tous les hyperliens HyperlinkClick et HyperlinkMouseOver contenus (dans tous les sous-objets IHyperlinkContainer).