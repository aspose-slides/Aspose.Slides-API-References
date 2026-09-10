---
title: Paragraph
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل فقرة نصية.
type: docs
url: /ar/com.aspose.slides/paragraph/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

يمثل فقرة نصية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Paragraph()](#Paragraph--) | ينشئ مثيلًا جديدًا من الفئة Paragraph بخصائص افتراضية. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | منشئ نسخة يinitializes مثيلًا جديدًا من الفئة Paragraph. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPortions()](#getPortions--) | يعيد مجموعة الأجزاء النصية. |
| [getParagraphFormat()](#getParagraphFormat--) | يعيد كائن التنسيق لهذه الفقرة. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يدمج المقاطع ذات التنسيق نفسه. |
| [getText()](#getText--) | يحصل أو يحدد النص العادي للفقرة. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يحدد النص العادي للفقرة. |
| [getRect()](#getRect--) | يحصل على إحداثيات المستطيل الذي يحد الفقرة. |
| [getLinesCount()](#getLinesCount--) | يحصل على عدد الأسطر في الفقرة. |
| [getImage()](#getImage--) | يعيد صورة للفقرة. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | يعيد صورة للفقرة بالمقياس المحدد. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | يعيد الشريحة الأصلية للفقرة. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأصلي للفقرة. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


ينشئ مثيلًا جديدًا من الفئة Paragraph بخصائص افتراضية.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


منشئ نسخة يinitializes مثيلًا جديدًا من الفئة Paragraph.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


يعيد مجموعة الأجزاء النصية. للقراءة فقط [IPortionCollection](../../com.aspose.slides/iportioncollection).

**القيمة المعادة:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


يعيد كائن التنسيق لهذه الفقرة. للقراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المعرفة للفقرة الحالية فقط، ولا تُطبق البيانات الموروثة.

للحصول على القيم الفعلية بما فيها القيم الموروثة استخدم طريقة [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**القيمة المعادة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


يدمج المقاطع ذات التنسيق نفسه.

### getText() {#getText--}
```
public final String getText()
```


يحصل أو يحدد النص العادي للفقرة. قابل للقراءة والكتابة String.

القيمة: النص.

**القيمة المعادة:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


يحصل أو يحدد النص العادي للفقرة. قابل للقراءة والكتابة String.

القيمة: النص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


يحصل على إحداثيات المستطيل الذي يحد الفقرة. يشمل المستطيل جميع أسطر النص في الفقرة، بما فيها الفارغة.

**القيمة المعادة:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


يحصل على عدد الأسطر في الفقرة.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المعادة:**
int - عدد الأسطر في الفقرة
### getImage() {#getImage--}
```
public final IImage getImage()
```


يعيد صورة للفقرة.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المعادة:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المرسومة، أو null إذا تعذر العثور على الفقرة في مجموعة الأصل، أو لا توجد حدود عرض صالحة، أو حدث خطأ أثناء رسم الصورة.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


يعيد صورة للفقرة بالمقياس المحدد.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | float | عامل المقياس الأفقي المطبق على صورة الفقرة. |
| scaleY | float | عامل المقياس الرأسي المطبق على صورة الفقرة. |

**القيمة المعادة:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المرسومة، أو null إذا تعذر العثور على الفقرة في مجموعة الأصل، أو لا توجد حدود عرض صالحة، أو حدث خطأ أثناء رسم الصورة.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير.

**القيمة المعادة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المعادة:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


يعيد الشريحة الأصلية للفقرة. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المعادة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


يعيد العرض الأصلي للفقرة. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المعادة:**
[IPresentation](../../com.aspose.slides/ipresentation)