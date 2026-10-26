---
title: TextFrameFormat
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يحتوي على خصائص formatTextFrameFormatting الخاصة بـ TextFrames.
type: docs
url: /ar/com.aspose.slides/textframeformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**كل الواجهات المنفذة:**  
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)  
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

يحتوي على خصائص formatTextFrameFormatting الخاصة بـ TextFrame.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | يفترض مثيلًا جديدًا من الفئة [TextFrameFormat](../../com.aspose.slides/textframeformat). |

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | يعيد نمط النص. |
| [getThreeDFormat()](#getThreeDFormat--) | يعيد كائن ThreeDFormat الذي يمثل خصائص تأثير 3D للنص. |
| [getMarginLeft()](#getMarginLeft--) | يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. |
| [getWrapText()](#getWrapText--) | صحيح إذا كان النص ملتفًا عند هوامش TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | صحيح إذا كان النص ملتفًا عند هوامش TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | يعيد أو يضبط النص المرجعي العمودي في TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | يعيد أو يضبط النص المرجعي العمودي في TextFrame. |
| [getCenterText()](#getCenterText--) | إذا كان NullableBool.True فإن النص يجب أن يكون متوسطًا أفقيًا داخل الصندوق. |
| [setCenterText(byte value)](#setCenterText-byte-) | إذا كان NullableBool.True فإن النص يجب أن يكون متوسطًا أفقيًا داخل الصندوق. |
| [getTextVerticalType()](#getTextVerticalType--) | يحدد اتجاه النص. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | يحدد اتجاه النص. |
| [getAutofitType()](#getAutofitType--) | يعيد أو يضبط وضعية التلائم التلقائي للنص. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | يعيد أو يضبط وضعية التلائم التلقائي للنص. |
| [getColumnCount()](#getColumnCount--) | يعيد أو يضبط عدد الأعمدة في منطقة النص. |
| [setColumnCount(int value)](#setColumnCount-int-) | يعيد أو يضبط عدد الأعمدة في منطقة النص. |
| [getColumnSpacing()](#getColumnSpacing--) | يعيد أو يضبط المسافة بين أعمدة النص في منطقة النص (نقاط). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | يعيد أو يضبط المسافة بين أعمدة النص في منطقة النص (نقاط). |
| [getRotationAngle()](#getRotationAngle--) | يحدد الدوران المخصص الذي يُطبق على النص داخل صندوق الحد. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | يحدد الدوران المخصص الذي يُطبق على النص داخل صندوق الحد. |
| [getTransform()](#getTransform--) | يحصل أو يضبط شكل التفاف النص. |
| [setTransform(byte value)](#setTransform-byte-) | يحصل أو يضبط شكل التفاف النص. |
| [getKeepTextFlat()](#getKeepTextFlat--) | يحصل أو يضبط الحفاظ على النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | يحصل أو يضبط الحفاظ على النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

يفترض مثيلًا جديدًا من الفئة [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**  
long

### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

يعيد نمط النص. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

يعيد كائن ThreeDFormat الذي يمثل خصائص تأثير 3d للنص. قراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // تعيين تحويل النص
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // تعيين البثق
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // تعيين الحد
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // تعيين العمق
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // تعيين المادة
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // تعيين الإضاءة
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // تعيين نوع الكاميرا
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

يعيد أو يضبط الهامش الأيسر (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

يعيد أو يضبط الهامش الأيمن (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

يعيد أو يضبط الهامش العلوي (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

يعيد أو يضبط الهامش السفلي (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

صحيح إذا كان النص ملفوفًا عند هوامش TextFrame. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**  
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

صحيح إذا كان النص ملفوفًا عند هوامش TextFrame. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

يعيد أو يضبط النص المرجعي العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**  
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

يعيد أو يضبط النص المرجعي العمودي في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

إذا كان NullableBool.True فإن النص يجب أن يكون متوسطًا أفقيًا داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

إذا كان NullableBool.True فإن النص يجب أن يكون متوسطًا أفقيًا داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

يحدد اتجاه النص. القيمة الناتجة من دوران النص البصري ملخصة من هذه الخاصية والزواية المخصصة في الخاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

يحدد اتجاه النص. القيمة الناتجة من دوران النص البصري ملخصة من هذه الخاصية والزواية المخصصة في الخاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

يعيد أو يضبط وضعية التلائم التلقائي للنص. قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> يعرض الكود العيني التالي كيفية تغيير حجم الشكل لملاءمة النص في عرض تقديمي PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
  
> يعرض الكود العيني التالي كيفية تقليص النص عند الفيض.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

يعيد أو يضبط وضعية التلائم التلقائي للنص. قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> يعرض الكود العيني التالي كيفية تغيير حجم الشكل لملاءمة النص في عرض تقديمي PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
  
> يعرض الكود العيني التالي كيفية تقليص النص عند الفيض.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

يعيد أو يضبط عدد الأعمدة في منطقة النص. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم تعيين القيمة إلى صفر. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة int.

--------------------

> ```
> يعرض الكود العيني التالي كيفية إضافة عمود في إطار النص داخل عرض تقديمي PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

يعيد أو يضبط عدد الأعمدة في منطقة النص. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم تعيين القيمة إلى صفر. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة int.

--------------------

> ```
> يعرض الكود العيني التالي كيفية إضافة عمود في إطار النص داخل عرض تقديمي PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

يعيد أو يضبط المسافة بين أعمدة النص في منطقة النص (نقاط). يجب أن يُطبق هذا فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم تعيين القيمة إلى صفر. قراءة/كتابة double.

**الإرجاع:**  
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

يعيد أو يضبط المسافة بين أعمدة النص في منطقة النص (نقاط). يجب أن يُطبق هذا فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة رقمًا موجبًا. وإلا سيتم تعيين القيمة إلى صفر. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

يحدد الدوران المخصص الذي يُطبق على النص داخل صندوق الحد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة من دوران النص البصري ملخصة من هذه الخاصية والنوع العمودي المسبق التعريف في الخاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> اعتبر الحالة حيث يكون لل shape دوران 90 درجة مع اتجاه عقارب الساعة مطبقًا عليه. 
>  بالإضافة إلى ذلك، يمتلك جسم النص نفسه دورانًا مقداره -90 درجة 
>  عكس اتجاه عقارب الساعة مطبقًا عليه. ثم سيظهر الشكل الناتج كما لو أنه
>  تم تدويره ولكن النص الموجود بداخله يبدو كما لو أنه لم يُدوَّر أبدا.
```

**الإرجاع:**  
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

يحدد الدوران المخصص الذي يُطبق على النص داخل صندوق الحد. إذا لم يُحدد، يُستخدم دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة من دوران النص البصري ملخصة من هذه الخاصية والنوع العمودي المسبق التعريف في الخاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> اعتبر الحالة التي يتم فيها تطبيق دوران 90 درجة باتجاه عقارب الساعة على الشكل. 
>  بالإضافة إلى ذلك، يمتلك جسم النص نفسه دورانًا قدره -90 درجة 
>  عكس اتجاه عقارب الساعة مطبّقًا عليه. ثم سيظهر الشكل الناتج كما لو أنه
>  تم تدويره لكن النص داخل الشكل سيظهر كما لو أنه لم يتم تدويره مطلقًا.
```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

يحصل أو يضبط شكل التفاف النص. قراءة/كتابة [TextShapeType](../../com.aspose.slides/textshapetype).

**الإرجاع:**  
byte

### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

يحصل أو يضبط شكل التفاف النص. قراءة/كتابة [TextShapeType](../../com.aspose.slides/textshapetype).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

يحصل أو يضبط الحفاظ على النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

يحصل أو يضبط الحفاظ على النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. قراءة/كتابة boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> هذا المثال يوضح الحصول على بعض خصائص تنسيق إطار النص الفعّالة.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).