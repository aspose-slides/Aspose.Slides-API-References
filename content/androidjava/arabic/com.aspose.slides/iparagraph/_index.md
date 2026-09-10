---
title: IParagraph
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل فقرة من نص.
type: docs
url: /ar/com.aspose.slides/iparagraph/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

يمثل فقرة من النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPortions()](#getPortions--) | إرجاع مجموعة من أجزاء النص. |
| [getParagraphFormat()](#getParagraphFormat--) | إرجاع كائن التنسيق لهذه الفقرة. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع السلاسل ذات التنسيق نفسه. |
| [getText()](#getText--) | يحصل أو يعيّن النص العادي للفقرة. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يعيّن النص العادي للفقرة. |
| [getRect()](#getRect--) | يحصل على إحداثيات المستطيل الذي يحد الفقرة. |
| [getLinesCount()](#getLinesCount--) | يحصل على عدد أسطر الفقرة. |
| [getImage()](#getImage--) | إرجاع صورة للفقرة. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | إرجاع صورة للفقرة بالمقياس المحدد. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

إرجاع مجموعة من أجزاء النص. للقراءة فقط [IPortionCollection](../../com.aspose.slides/iportioncollection).

**الإرجاع:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

إرجاع كائن التنسيق لهذه الفقرة. للقراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**الإرجاع:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

يجمع السلاسل ذات التنسيق نفسه.

### getText() {#getText--}
```
public abstract String getText()
```

يحصل أو يعيّن النص العادي للفقرة. قابل للقراءة والكتابة String.

القيمة: النص.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

يحصل أو يعيّن النص العادي للفقرة. قابل للقراءة والكتابة String.

القيمة: النص.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

يحصل على إحداثيات المستطيل الذي يحد الفقرة. المستطيل يتضمن جميع أسطر النص في الفقرة، بما في ذلك الفارغة.

**الإرجاع:**
android.graphics.RectF - مستطيل يحد الفقرة android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

يحصل على عدد أسطر الفقرة.

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


**الإرجاع:**
int - عدد الأسطر في الفقرة
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

إرجاع صورة للفقرة.

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


**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المُرسومة، أو null إذا تعذر العثور على الفقرة في المجموعة الأصلية، أو لا تحتوي على حدود عرض صالحة، أو حدث خطأ أثناء رسم الصورة.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

إرجاع صورة للفقرة بالمقياس المحدد.

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| scaleX | float | عامل المقياس الأفقي المطبق على صورة الفقرة. |
| scaleY | float | عامل المقياس الرأسي المطبق على صورة الفقرة. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المُرسومة، أو null إذا تعذر العثور على الفقرة في المجموعة الأصلية، أو لا تحتوي على حدود عرض صالحة، أو حدث خطأ أثناء رسم الصورة.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير.

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

يحدد خصائص الجزء التي سيتم استخدامها إذا تم إدراج جزء آخر بعد الأخير.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |