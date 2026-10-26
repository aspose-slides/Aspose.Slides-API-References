---
title: IChartTitle
second_title: Aspose.Slides pour Android via la Référence de l'API Java
description: Représente les propriétés du titre du graphique.
type: docs
url: /fr/com.aspose.slides/icharttitle/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Représente les propriétés du titre du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Détermine si d'autres éléments du graphique peuvent chevaucher le titre. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Détermine si d'autres éléments du graphique peuvent chevaucher le titre. |
| [getFormat()](#getFormat--) | Renvoie les styles de remplissage, de ligne et d'effet d'un titre. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Détermine si d'autres éléments du graphique peuvent chevaucher le titre. Lecture/écriture boolean.

**Renvoie:** 
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Détermine si d'autres éléments du graphique peuvent chevaucher le titre. Lecture/écriture boolean.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Renvoie les styles de remplissage, de ligne et d'effet d'un titre. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie:** 
[IFormat](../../com.aspose.slides/iformat)