---
title: IInkBrush
second_title: Aspose.Slides pour Java Référence de l'API
description: Représente le pinceau de traçage.
type: docs
url: /fr/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Représente le pinceau de traçage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtient ou définit la couleur du pinceau pour une ligne. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Obtient ou définit la couleur du pinceau pour une ligne. |
| [getSize()](#getSize--) | Obtient ou définit la taille du pinceau pour une ligne en points. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Obtient ou définit la taille du pinceau pour une ligne en points. |
| [getInkEffect()](#getInkEffect--) | Obtient le type d'effet d'encre (p. ex., Galaxy, Gold, Silver) qui définit le style visuel du tracé d'encre. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Obtient ou définit la couleur du pinceau pour une ligne.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Obtient ou définit la couleur du pinceau pour une ligne.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Obtient ou définit la taille du pinceau pour une ligne en points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

Obtient ou définit la taille du pinceau pour une ligne en points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Obtient le type d'effet d'encre (p. ex., Galaxy, Gold, Silver) qui définit le style visuel du tracé d'encre. La valeur est analysée à partir de la propriété du pinceau "inkEffects". Si aucun effet reconnu n'est spécifié, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) est retourné.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
int