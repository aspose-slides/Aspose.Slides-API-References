---
title: AutoShape
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل AutoShape.
type: docs
url: /ar/com.aspose.slides/autoshape/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

يمثل AutoShape.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns autoshape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

يعيد أقفال الشكل. للقراءة فقط [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**القيمة المرجعة:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

يعيد أقفال autoshape. للقراءة فقط [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**القيمة المرجعة:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

يعيد كائن TextFrame لـ AutoShape. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

يحدد ما إذا كان يجب ملء هذا autoshape بخلفية الشريحة بدلاً من ما تم تحديده بواسطة النمط أو تنسيق التعبئة. قابل للقراءة/الكتابة (boolean).

**القيمة المرجعة:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

يحدد ما إذا كان يجب ملء هذا autoshape بخلفية الشريحة بدلاً من ما تم تحديده بواسطة النمط أو تنسيق التعبئة. قابل للقراءة/الكتابة (boolean).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

يضيف TextFrame جديدًا إلى الشكل. إذا كان الشكل يحتوي بالفعل على TextFrame فسيقوم ببساطة بتغيير نصه.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // إنشاء كائن Presentation
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى في Presentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // إضافة AutoShape مع تعيين النوع ك Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // إضافة TextFrame إلى Rectangle
>      ashp.addTextFrame(" ");
>      // الوصول إلى TextFrame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // إنشاء كائن Paragraph لإطار النص
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // إنشاء كائن Portion للفقرة
>      IPortion portion = para.getPortions().get_Item(0);
>      // ضبط النص
>      portion.setText("Aspose TextBox");
>      // حفظ العرض التقديمي إلى القرص
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى في Presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // إضافة AutoShape مع تعيين النوع ك Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // إضافة TextFrame إلى Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // الحصول على تنسيق النص في TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // تحديد عدد الأعمدة في TextFrame
>      format.setColumnCount(3);
>      // تحديد المسافة بين الأعمدة
>      format.setColumnSpacing(10);
>      // حفظ العرض التقديمي
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الافتراضي لـ TextFrame جديد. |

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

يحدد ما إذا كان الشكل مربع نص.

--------------------

إذا لم يُحدد أن الشكل مربع نص فهذا لا يعني أنه لا يمكن أن يحتوي على نص مرفق به. مربع النص هو مجرد شكل متخصص بخصائص معينة.

**القيمة المرجعة:**
boolean