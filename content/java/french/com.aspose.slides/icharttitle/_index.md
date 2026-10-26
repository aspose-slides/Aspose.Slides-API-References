---
title: IChartTitle
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés du titre du diagramme.
type: docs
url: /fr/com.aspose.slides/icharttitle/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Représente les propriétés du titre du diagramme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Détermine si d’autres éléments du diagramme sont autorisés à chevaucher le titre. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Détermine si d’autres éléments du diagramme sont autorisés à chevaucher le titre. |
| [getFormat()](#getFormat--) | Renvoie les styles de remplissage, de ligne et d’effet d’un titre. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Détermine si d’autres éléments du diagramme sont autorisés à chevaucher le titre. Lecture/écriture booléen.

**Renvoie :**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Détermine si d’autres éléments du diagramme sont autorisés à chevaucher le titre. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Renvoie les styles de remplissage, de ligne et d’effet d’un titre. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)