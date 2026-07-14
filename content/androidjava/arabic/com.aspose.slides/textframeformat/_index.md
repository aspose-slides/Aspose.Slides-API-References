---
title: TextFrameFormat
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يحتوي على خصائص formatTextFrameFormatting الخاصة بـ TextFrames.
type: docs
url: /ar/com.aspose.slides/textframeformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

يحتوي على خصائص formatTextFrameFormatting الخاصة بـ TextFrame.
## المُنشئات

| المنشيء | الوصف |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | ينشئ مثالا جديدًا من الفئة [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | إرجاع نمط النص. |
| [getThreeDFormat()](#getThreeDFormat--) | إرجاع كائن ThreeDFormat الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص. |
| [getMarginLeft()](#getMarginLeft--) | إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | إرجاع أو تعيين الهامش الأعلى (نقاط) في TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | إرجاع أو تعيين الهامش الأعلى (نقاط) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. |
| [getWrapText()](#getWrapText--) | صحيح إذا تم لف النص عند هوامش TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | صحيح إذا تم لف النص عند هوامش TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | إرجاع أو تعيين النص العمودي المرتكز في TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | إرجاع أو تعيين النص العمودي المرتكز في TextFrame. |
| [getCenterText()](#getCenterText--) | إذا كان NullableBool.True فإن النص يجب أن يُوسّط أفقياً داخل الصندوق. |
| [setCenterText(byte value)](#setCenterText-byte-) | إذا كان NullableBool.True فإن النص يجب أن يُوسّط أفقياً داخل الصندوق. |
| [getTextVerticalType()](#getTextVerticalType--) | تحديد اتجاه النص. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | تحديد اتجاه النص. |
| [getAutofitType()](#getAutofitType--) | إرجاع أو تعيين وضع الملاءمة التلقائية للنص. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | إرجاع أو تعيين وضع الملاءمة التلقائية للنص. |
| [getColumnCount()](#getColumnCount--) | إرجاع أو تعيين عدد الأعمدة في مساحة النص. |
| [setColumnCount(int value)](#setColumnCount-int-) | إرجاع أو تعيين عدد الأعمدة في مساحة النص. |
| [getColumnSpacing()](#getColumnSpacing--) | إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). |
| [getRotationAngle()](#getRotationAngle--) | تحديد دوران مخصص يُطبق على النص داخل الصندوق المحدد. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | تحديد دوران مخصص يُطبق على النص داخل الصندوق المحدد. |
| [getTransform()](#getTransform--) | إرجاع أو تعيين شكل لف النص. |
| [setTransform(byte value)](#setTransform-byte-) | إرجاع أو تعيين شكل لف النص. |
| [getKeepTextFlat()](#getKeepTextFlat--) | إرجاع أو تعيين إبقاء النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | إرجاع أو تعيين إبقاء النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. |
| [getEffective()](#getEffective--) | إرجاع بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


ينشئ مثالا جديدًا من الفئة [TextFrameFormat](../../com.aspose.slides/textframeformat).

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


إرجاع نمط النص. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


إرجاع كائن ThreeDFormat الذي يمثل خصائص التأثير ثلاثي الأبعاد للنص. قراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // ضبط تحويل النص
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // ضبط البثق
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // ضبط الحدود
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // ضبط العمق
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // ضبط المادة
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // ضبط الإضاءة
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // ضبط نوع الكاميرا
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


إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


إرجاع أو تعيين الهامش الأيسر (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


إرجاع أو تعيين الهامش الأيمن (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


إرجاع أو تعيين الهامش الأعلى (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


إرجاع أو تعيين الهامش الأعلى (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. قراءة/كتابة double.

**الإرجاع:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


إرجاع أو تعيين الهامش السفلي (نقاط) في TextFrame. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


صحيح إذا تم لف النص عند هوامش TextFrame. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

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


صحيح إذا تم لف النص عند هوامش TextFrame. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


إرجاع أو تعيين النص العمودي المرتكز في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


إرجاع أو تعيين النص العمودي المرتكز في TextFrame. قراءة/كتابة [TextAnchorType](../../com.aspose.slides/textanchortype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


إذا كان NullableBool.True فإن النص يجب أن يُوسّط أفقياً داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


إذا كان NullableBool.True فإن النص يجب أن يُوسّط أفقياً داخل الصندوق. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


تحديد اتجاه النص. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والزاوية المخصصة في خاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


تحديد اتجاه النص. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والزاوية المخصصة في خاصية RotationAngle. قراءة/كتابة [TextVerticalType](../../com.aspose.slides/textverticaltype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


إرجاع أو تعيين وضع الملاءمة التلقائية للنص. قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
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
>  The following sample code shows how to shrink text on overflow.
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


إرجاع أو تعيين وضع الملاءمة التلقائية للنص. قراءة/كتابة [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
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
>  The following sample code shows how to shrink text on overflow.
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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


إرجاع أو تعيين عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة عددًا موجبًا. وإلا سيتم ضبط القيمة إلى صفر. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة int.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة عمود في إطار النص داخل عرض PowerPoint.
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


إرجاع أو تعيين عدد الأعمدة في مساحة النص. يجب أن تكون هذه القيمة عددًا موجبًا. وإلا سيتم ضبط القيمة إلى صفر. القيمة 0 تعني قيمة غير معرفة. قراءة/كتابة int.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة عمود في إطار النص داخل عرض PowerPoint.
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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). يجب أن يطبق هذا فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة عددًا موجبًا. وإلا سيتم ضبط القيمة إلى صفر. قراءة/كتابة double.

**الإرجاع:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


إرجاع أو تعيين المسافة بين أعمدة النص في مساحة النص (نقاط). يجب أن يطبق هذا فقط عندما يكون هناك أكثر من عمود واحد. يجب أن تكون هذه القيمة عددًا موجبًا. وإلا سيتم ضبط القيمة إلى صفر. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


تحديد دوران مخصص يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يتم استخدام دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والنوع العمودي المحدد مسبقًا في خاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> تخيل الحالة التي يكون فيها الشكل قد تم تطبيق دوران قدره 90 درجة باتجاه عقارب الساعة عليه. 
>  بالإضافة إلى ذلك، جسم النص نفسه لديه دوران قدره -90 درجة 
>  عكس اتجاه عقارب الساعة مطبق عليه. ثم سيظهر الشكل الناتج كأن
>  يكون مدورًا لكن النص داخله سيظهر كما لو أنه لم يُدار مطلقًا.
```

**الإرجاع:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


تحديد دوران مخصص يُطبق على النص داخل الصندوق المحدد. إذا لم يُحدد، يتم استخدام دوران الشكل المرافق. إذا تم تحديده، يُطبق بشكل مستقل عن الشكل. أي أن الشكل يمكن أن يكون له دوران بالإضافة إلى دوران النص نفسه. القيمة الناتجة لدوران النص البصري ملخصة من هذه الخاصية والنوع العمودي المحدد مسبقًا في خاصية TextVerticalType. قراءة/كتابة float.

--------------------

> ```
> تخيل الحالة التي يكون فيها الشكل قد تم تطبيق دوران قدره 90 درجة باتجاه عقارب الساعة عليه.
>  بالإضافة إلى ذلك، جسم النص نفسه لديه دوران قدره -90 درجة
>  عكس اتجاه عقارب الساعة مطبق عليه. ثم سيظهر الشكل الناتج كما لو
>  كان مدورًا لكن النص داخله سيظهر كما لو أنه لم يُدار مطلقًا.
```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```


إرجاع أو تعيين شكل لف النص. قراءة/كتابة [TextShapeType](../../com.aspose.slides/textshapetype).

**الإرجاع:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


إرجاع أو تعيين شكل لف النص. قراءة/كتابة [TextShapeType](../../com.aspose.slides/textshapetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


إرجاع أو تعيين إبقاء النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


إرجاع أو تعيين إبقاء النص مسطحًا حتى إذا تم تطبيق تأثير دوران ثلاثي الأبعاد. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


إرجاع بيانات تنسيق إطار النص الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
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
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - أحد [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).