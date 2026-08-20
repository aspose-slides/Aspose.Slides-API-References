---
title: IParagraph
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل فقرة من نص.
type: docs
url: /ar/com.aspose.slides/iparagraph/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

يمثل فقرة من النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPortions()](#getPortions--) | يعيد مجموعة من أجزاء النص. |
| [getParagraphFormat()](#getParagraphFormat--) | يعيد كائن التنسيق لهذه الفقرة. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ينضم المقاطع ذات التنسيق نفسه. |
| [getText()](#getText--) | يحصل أو يضبط النص العادي للفقرة. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط النص العادي للفقرة. |
| [getRect()](#getRect--) | يحصل على إحداثيات المستطيل الذي يحد الفقرة. |
| [getLinesCount()](#getLinesCount--) | يحصل على عدد الأسطر في الفقرة. |
| [getImage()](#getImage--) | يعيد صورة للفقرة. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | يعيد صورة للفقرة بالمقياس المحدد. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | يحدد خصائص الجزء التي ستُستخدم إذا تم إدراج جزء آخر بعد الأخير. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | يحدد خصائص الجزء التي ستُستخدم إذا تم إدراج جزء آخر بعد الأخير. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

يعيد مجموعة من أجزاء النص. للقراءة فقط [IPortionCollection](../../com.aspose.slides/iportioncollection).

**القيمة المرجعة:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

يعيد كائن التنسيق لهذه الفقرة. للقراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**القيمة المرجعة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

ينضم المقاطع ذات التنسيق نفسه.

### getText() {#getText--}
```
public abstract String getText()
```

يحصل أو يضع النص العادي للفقرة. قراءة/كتابة String.

القيمة: النص.

**القيمة المرجعة:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

يحصل أو يضع النص العادي للفقرة. قراءة/كتابة String.

القيمة: النص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

يحصل على إحداثيات المستطيل الذي يحد الفقرة. المستطيل يشمل جميع أسطر النص في الفقرة، بما في ذلك الفارغة.

**القيمة المرجعة:**
java.awt.geom.Rectangle2D.Float - المستطيل الذي يحد الفقرة java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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


**القيمة المرجعة:**
int - عدد الأسطر في الفقرة
### getImage() {#getImage--}
```
public abstract IImage getImage()
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


**القيمة المرجعة:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المرسومة، أو null إذا لم يمكن العثور على الفقرة في مجموعة الوالد الخاصة بها، أو لا توجد حدود عرض صالحة، أو حدث خطأ أثناء عرض الصورة.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
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
| scaleX | float | معامل التحجيم الأفقي المطبق على صورة الفقرة. |
| scaleY | float | معامل التحجيم العمودي المطبق على صورة الفقرة. |

**القيمة المرجعة:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المرسومة، أو null إذا لم يمكن العثور على الفقرة في مجموعة الوالد الخاصة بها، أو لا توجد حدود عرض صالحة، أو حدث خطأ أثناء عرض الصورة.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

حدد خصائص الجزء التي ستُستخدم إذا تم إدراج جزء آخر بعد الأخير.

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

حدد خصائص الجزء التي ستُستخدم إذا تم إدراج جزء آخر بعد الأخير.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |