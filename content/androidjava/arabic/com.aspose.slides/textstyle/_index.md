---
title: TextStyle
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: هذه الفئة تحتوي على خصائص تنسيق نمط النص.
type: docs
url: /ar/com.aspose.slides/textstyle/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

هذه الفئة تحتوي على خصائص تنسيق نمط النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | إذا كان مستوى النمط موجودًا فسيتم إرجاعه، وإلا فسيتم إرجاع null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | خصائص الفقرة الافتراضية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق نمط النص الفعّال مع تطبيق الوراثة. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. قراءة فقط long.

**الإرجاع:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


إذا كان مستوى النمط موجودًا فسيتم إرجاعه، وإلا فسيتم إرجاع null.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للمستوى. يجب أن يكون في الفاصل 0..8. |

**الإرجاع:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - تنسيق المستوى [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


خصائص الفقرة الافتراضية. قراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**الإرجاع:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


يحصل على بيانات تنسيق نمط النص الفعّال مع تطبيق الوراثة.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).