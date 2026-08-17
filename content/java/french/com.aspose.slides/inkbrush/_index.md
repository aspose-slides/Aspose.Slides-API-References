---
title: InkBrush
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un objet inkBrush.
type: docs
url: /fr/com.aspose.slides/inkbrush/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

Représente un objet inkBrush.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtient ou définit la couleur du pinceau pour une ligne. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Obtient ou définit la couleur du pinceau pour une ligne. |
| [getSize()](#getSize--) | Obtient ou définit la taille du pinceau pour une ligne en points. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Obtient ou définit la taille du pinceau pour une ligne en points. |
| [getInkEffect()](#getInkEffect--) | Obtient le type d'effet d'encre (par ex., Galaxy, Gold, Silver) qui définit le style visuel du trait d'encre. |

### getColor() {#getColor--}
```
public final Color getColor()
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

**Retour:**  
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
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

**Retour:**  
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Obtient le type d'effet d'encre (par ex., Galaxy, Gold, Silver) qui définit le style visuel du trait d'encre. La valeur est analysée à partir de la propriété du pinceau « inkEffects ». Si aucun effet reconnu n'est spécifié, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) est retourné.

**Retour:**  
int