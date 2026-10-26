---
title: InkBrush
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل كائن inkBrush.
type: docs
url: /ar/com.aspose.slides/inkbrush/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

يمثل كائن inkBrush.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يحصل على لون الفرشاة أو يضبطه لخط. |
| [setColor(Color value)](#setColor-java.awt.Color-) | يحصل على لون الفرشاة أو يضبطه لخط. |
| [getSize()](#getSize--) | يحصل على حجم الفرشاة أو يضبطه لخط بالنقاط. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | يحصل على حجم الفرشاة أو يضبطه لخط بالنقاط. |
| [getInkEffect()](#getInkEffect--) | يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لضربة الحبر. |

### getColor() {#getColor--}
```
public final Color getColor()
```

يحصل على لون الفرشاة أو يضبطه لخط.

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


**الإرجاع:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

يحصل على لون الفرشاة أو يضبطه لخط.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

يحصل على حجم الفرشاة أو يضبطه لخط بالنقاط.

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


**الإرجاع:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

يحصل على حجم الفرشاة أو يضبطه لخط بالنقاط.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لضربة الحبر. يتم استخراج القيمة من خاصية الفرشاة "inkEffects". إذا لم يتم تحديد أي تأثير معروف، يتم إرجاع [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**الإرجاع:**
int