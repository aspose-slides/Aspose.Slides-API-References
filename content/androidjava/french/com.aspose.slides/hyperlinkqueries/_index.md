---
title: HyperlinkQueries
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Fournit un accès facile aux hyperliens contenus.
type: docs
url: /fr/com.aspose.slides/hyperlinkqueries/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

Fournissez un accès facile aux hyperliens contenus.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Supprime tous les hyperliens HyperlinkClick et HyperlinkMouseOver contenus (dans tous les sous-objets IHyperlinkContainer). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkClick non nul. Avec l'objet IHyperlinkContainer fourni, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l'interface IHyperlinkContainer.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. Avec l'objet IHyperlinkContainer fourni, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l'interface IHyperlinkContainer.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Récupère tous les sous-objets IHyperlinkContainer qui contiennent un HyperlinkMouseOver non nul. Avec l'objet IHyperlinkContainer fourni, vous pouvez gérer son hyperlien (lecture, mise à jour ou suppression). Voir l'interface IHyperlinkContainer.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

Supprime tous les hyperliens HyperlinkClick et HyperlinkMouseOver contenus (dans tous les sous-objets IHyperlinkContainer).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourne l'objet Parent_Immediate. Lecture-seule IDOMObject.

**Retourne :**
com.aspose.slides.IDOMObject