---
title: Paragraph
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل فقرة نصية.
type: docs
url: /ar/com.aspose.slides/paragraph/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

يمثل فقرة نصية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initializes a new instance of the Paragraph class with default properties. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Copy constructor that initializes a new instance of a Paragraph class. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getPortions()](#getPortions--) | Returns the collection of a text portions. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns the formatting object for this paragraph. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting. |
| [getText()](#getText--) | Gets or sets the the plain text of a paragraph. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the the plain text of a paragraph. |
| [getRect()](#getRect--) | Get coordinates of rect that bounds paragraph. |
| [getLinesCount()](#getLinesCount--) | Get number of lines in a paragraph. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returns the parent slide of a paragraph. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a paragraph. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

ينشئ كائنًا جديدًا من الفئة Paragraph بخصائص افتراضية.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

منشئ نسخة يخلق كائنًا جديدًا من الفئة Paragraph.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |
### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

يعيد مجموعة مقاطع النص. للقَقراء فقط [IPortionCollection](../../com.aspose.slides/iportioncollection).

**القيمة المرجعة:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

يعيد كائن التنسيق لهذه الفقرة. للقَقراء فقط [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

كائن التنسيق يحتوي على معلمات التنسيق المعرفة للفقرة الحالية فقط، ولا تُطبق البيانات المورثة.

للحصول على القيم الفعلية بما في ذلك الموروثة استخدم الطريقة [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**القيمة المرجعة:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

يجمع السلاسل ذات التنسيق نفسه.
### getText() {#getText--}
```
public final String getText()
```

يحصل أو يضبط النص العادي للفقرة. قراءة/كتابة String.

القيمة: النص.

**القيمة المرجعة:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

يحصل أو يضبط النص العادي للفقرة. قراءة/كتابة String.

القيمة: النص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public final RectF getRect()
```

يحصل على إحداثيات المستطيل الذي يحد الفقرة. يشمل المستطيل جميع أسطر النص في الفقرة، بما في ذلك الفارغة.

**القيمة المرجعة:**
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

**القيمة المرجعة:**
int - عدد الأسطر في الفقرة
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

يحدد خصائص الجزء التي ستُستعمل إذا تم إدراج جزء آخر بعد الأخير.

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

يحدد خصائص الجزء التي ستُستعمل إذا تم إدراج جزء آخر بعد الأخير.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقَقراء فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأصلية للفقرة. للقَقراء فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأصل للفقرة. للقَقراء فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)