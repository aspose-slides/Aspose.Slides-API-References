---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: تمثّل فرشاة التتبع.
type: docs
url: /ar/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

تمثّل فرشاة التتبع.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يحصل أو يعيّن لون الفرشاة لخط. |
| [setColor(Color value)](#setColor-java.awt.Color-) | يحصل أو يعيّن لون الفرشاة لخط. |
| [getSize()](#getSize--) | يحصل أو يعيّن حجم الفرشاة لخط بالنقاط. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | يحصل أو يعيّن حجم الفرشاة لخط بالنقاط. |
| [getInkEffect()](#getInkEffect--) | يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لضربة الحبر. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


يحصل أو يعيّن لون الفرشاة لخط.

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

**القيمة المرجعة:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


يحصل أو يعيّن لون الفرشاة لخط.

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
public abstract Dimension2D getSize()
```


يحصل أو يعيّن حجم الفرشاة لخط بالنقاط.

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

**القيمة المرجعة:**  
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


يحصل أو يعيّن حجم الفرشاة لخط بالنقاط.

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
public abstract int getInkEffect()
```


يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لضربة الحبر. يتم تحليل القيمة من خاصية الفرشاة "inkEffects". إذا لم يتم تحديد أي تأثير معروف، يتم إرجاع [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

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

**القيمة المرجعة:**  
int