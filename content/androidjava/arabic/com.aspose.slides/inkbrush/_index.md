---
title: InkBrush
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل كائن inkBrush.
type: docs
url: /ar/com.aspose.slides/inkbrush/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

يمثل كائن inkBrush.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يحصل أو يضبط لون الفرشاة للخط. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | يحصل أو يضبط لون الفرشاة للخط. |
| [getSize()](#getSize--) | يحصل أو يضبط حجم الفرشاة للخط بالنقاط. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | يحصل أو يضبط حجم الفرشاة للخط بالنقاط. |
| [getInkEffect()](#getInkEffect--) | يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لسطر الحبر. |
### getColor() {#getColor--}
```
public final Integer getColor()
```


يحصل أو يضبط لون الفرشاة للخط.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


يحصل أو يضبط لون الفرشاة للخط.

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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


يحصل أو يضبط حجم الفرشاة للخط بالنقاط.

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

**القيمة المرجعة:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


يحصل أو يضبط حجم الفرشاة للخط بالنقاط.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


يحصل على نوع تأثير الحبر (مثل Galaxy، Gold، Silver) الذي يحدد النمط البصري لسطر الحبر. يتم استخراج القيمة من خاصية الفرشاة "inkEffects". إذا لم يتم تحديد تأثير معروف، يتم إرجاع [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**القيمة المرجعة:**
int