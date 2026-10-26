---
title: AutoShape
second_title: مرجع API Aspose.Slides للـ Java
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
| [getShapeLock()](#getShapeLock--) | يعيد أقفال الشكل. |
| [getAutoShapeLock()](#getAutoShapeLock--) | يعيد أقفال الـ AutoShape. |
| [getTextFrame()](#getTextFrame--) | يعيد كائن TextFrame للـ AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | يحدد ما إذا كان يجب ملء هذا الـ AutoShape بخلفية الشريحة بدلاً من ما يحدده النمط أو تنسيق التعبئة. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | يحدد ما إذا كان يجب ملء هذا الـ AutoShape بخلفية الشريحة بدلاً من ما يحدده النمط أو تنسيق التعبئة. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | يضيف TextFrame جديد إلى الشكل. |
| [isTextBox()](#isTextBox--) | يحدد ما إذا كان الشكل مربع نص. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

يعيد أقفال الشكل. للقراءة فقط [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**الإرجاع:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

يعيد أقفال الـ AutoShape. للقراءة فقط [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**الإرجاع:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

يعيد كائن TextFrame للـ AutoShape. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

يحدد ما إذا كان يجب ملء هذا الـ AutoShape بخلفية الشريحة بدلاً من ما يحدده النمط أو تنسيق التعبئة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

يحدد ما إذا كان يجب ملء هذا الـ AutoShape بخلفية الشريحة بدلاً من ما يحدده النمط أو تنسيق التعبئة. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

يضيف TextFrame جديد إلى الشكل. إذا كان الشكل يحتوي بالفعل على TextFrame فسيتم فقط تغيير نصه.

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
>      // يحصل على الشريحة الأولى في العرض التقديمي
>      ISlide sld = pres.getSlides().get_Item(0);
>      // يضيف AutoShape بنوع Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // يضيف TextFrame إلى المستطيل
>      ashp.addTextFrame(" ");
>      // الوصول إلى TextFrame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // ينشئ كائن Paragraph لإطار النص
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // ينشئ كائن Portion للفقرة
>      IPortion portion = para.getPortions().get_Item(0);
>      // يضبط النص
>      portion.setText("Aspose TextBox");
>      // يحفظ العرض التقديمي إلى القرص
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // يحصل على الشريحة الأولى في العرض التقديمي
>      ISlide slide = pres.getSlides().get_Item(0);
>      // يضيف AutoShape بنوع Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // يضيف TextFrame إلى المستطيل
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // يحصل على تنسيق النص الخاص بـ TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // يحدد عدد الأعمدة في TextFrame
>      format.setColumnCount(3);
>      // يحدد المسافة بين الأعمدة
>      format.setColumnSpacing(10);
>      // يحفظ العرض التقديمي
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الافتراضي لـ TextFrame الجديد. |

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

يحدد ما إذا كان الشكل مربع نص.

--------------------

إذا لم يُحدد الشكل بأنه مربع نص فهذا لا يعني أنه لا يمكن أن يحتوي على نص. مربع النص هو مجرد شكل متخصص بخصائص محددة.

**الإرجاع:**
boolean