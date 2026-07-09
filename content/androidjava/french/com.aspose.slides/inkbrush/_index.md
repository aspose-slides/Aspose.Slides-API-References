---
title: InkBrush
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un objet inkBrush.
type: docs
url: /fr/com.aspose.slides/inkbrush/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Représente un objet inkBrush.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtient ou définit la couleur du pinceau pour une ligne. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Obtient ou définit la couleur du pinceau pour une ligne. |
| [getSize()](#getSize--) | Obtient ou définit la taille du pinceau pour une ligne en points. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Obtient ou définit la taille du pinceau pour une ligne en points. |
| [getInkEffect()](#getInkEffect--) | Obtient le type d'effet d'encre (par ex., Galaxy, Gold, Silver) qui définit le style visuel du trait d'encre. |
### getColor() {#getColor--}
```
public final Integer getColor()
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

**Returns:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Gets or sets the brush color for a line.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

Gets or sets the brush size for a line in points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

Gets or sets the brush size for a line in points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()


Obtient le type d'effet d'encre (par ex., Galaxy, Gold, Silver) qui définit le style visuel du trait d'encre. La valeur est analysée à partir de la propriété du pinceau "inkEffects". Si aucun effet reconnu n'est spécifié, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) est renvoyé.

**Retour :**
int