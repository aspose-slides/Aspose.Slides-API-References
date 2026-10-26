---
title: Paragraph
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل فقرة نصية.
type: docs
url: /ar/com.aspose.slides/paragraph/
---
**Inheritance:**  
الوراثة:
java.lang.Object

**All Implemented Interfaces:**  
جميع الواجهات التي تم تنفيذها:
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

يمثل فقرة نصية.
## Constructors
## المنشئات

| Constructor | Description |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initializes a new instance of the Paragraph class with default properties. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Copy constructor that initializes a new instance of a Paragraph class. |

## Methods
## الطرق

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Returns the collection of a text portions. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns the formatting object for this paragraph. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting. |
| [getText()](#getText--) | Gets or sets the the plain text of a paragraph. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the the plain text of a paragraph. |
| [getRect()](#getRect--) | Get coordinates of rect that bounds paragraph. |
| [getLinesCount()](#getLinesCount--) | Get number of lines in a paragraph. |
| [getImage()](#getImage--) | Returns an image of the paragraph. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returns an image of the paragraph with the specified scale. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returns the parent slide of a paragraph. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a paragraph. |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

يُنشئ مثالًا جديدًا من الفئة Paragraph بالخصائص الافتراضية.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

منشئ نسخ يخلق مثالًا جديدًا من الفئة Paragraph.

**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

إرجاع مجموعة من أجزاء النص. للقراءة فقط [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Returns:**  
**الإرجاع:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

إرجاع كائن التنسيق لهذه الفقرة. للقراءة فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المعرفة للفقرة الحالية فقط، ولا يتم تطبيق البيانات الموروثة.

للحصول على القيم الفعلية بما في ذلك الموروثة، استخدم الطريقة [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Returns:**  
**الإرجاع:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق.

### getText() {#getText--}
```
public final String getText()
```

الحصول على أو تعيين النص العادي لفقرة. للقراءة/الكتابة String.

القيمة: النص.

**Returns:**  
**الإرجاع:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

الحصول على أو تعيين النص العادي لفقرة. للقراءة/الكتابة String.

القيمة: النص.

**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

الحصول على إحداثيات المستطيل الذي يحد الفقرة. يشمل المستطيل جميع أسطر النص في الفقرة، بما في ذلك الأسطر الفارغة.

**Returns:**  
**الإرجاع:**
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

الحصول على عدد الأسطر في الفقرة.

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


**Returns:**  
**الإرجاع:**
int - Lines count in a paragraph

### getImage() {#getImage--}
```
public final IImage getImage()
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


**Returns:**  
**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المرسومة، أو null إذا لم يتم العثور على الفقرة في مجموعة الوالد، أو لا توجد حدود عرض صحيحة، أو حدث خطأ أثناء عرض الصورة.

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
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


**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | عامل المقياس الأفقي المطبق على صورة الفقرة. |
| scaleY | float | عامل المقياس العمودي المطبق على صورة الفقرة. |

**Returns:**  
**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - صورة تحتوي على الفقرة المرسومة، أو null إذا لم يتم العثور على الفقرة في مجموعة الوالد، أو لا توجد حدود عرض صحيحة، أو حدث خطأ أثناء عرض الصورة.

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

تحديد خصائص الجزء التي يجب استخدامها إذا تم إدراج جزء آخر بعد الأخير.

**Returns:**  
**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

تحديد خصائص الجزء التي يجب استخدامها إذا تم إدراج جزء آخر بعد الأخير.

**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**Returns:**  
**الإرجاع:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

إرجاع الشريحة الأم للفقرة. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**  
**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

إرجاع العرض التقديمي الأم للفقرة. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**  
**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)