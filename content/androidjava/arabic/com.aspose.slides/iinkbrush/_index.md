---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل فرشاة التتبع.
type: docs
url: /ar/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

يمثل فرشاة التتبع.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يحصل أو يضبط لون الفرشاة لخط. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | يحصل أو يضبط لون الفرشاة لخط. |
| [getSize()](#getSize--) | يحصل أو يضبط حجم الفرشاة لخط بالنقاط. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | يحصل أو يضبط حجم الفرشاة لخط بالنقاط. |
| [getInkEffect()](#getInkEffect--) | يحصل على نوع تأثير الحبر (مثل Galaxy, Gold, Silver) الذي يحدد النمط البصري لضربة الحبر. |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

يحصل أو يضبط لون الفرشاة لخط.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

يحصل أو يضبط لون الفرشاة لخط.

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
public abstract SizeF getSize()
```

يحصل أو يضبط حجم الفرشاة لخط بالنقاط.

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


**الإرجاع:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```

يحصل أو يضبط حجم الفرشاة لخط بالنقاط.

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
public abstract int getInkEffect()
```

يحصل على نوع تأثير الحبر (مثل Galaxy, Gold, Silver) الذي يحدد النمط البصري لضربة الحبر. يتم استخراج القيمة من خاصية الفرشاة "inkEffects". إذا لم يتم تحديد أي تأثير معروف، يتم إرجاع [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

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

**الإرجاع:**
int