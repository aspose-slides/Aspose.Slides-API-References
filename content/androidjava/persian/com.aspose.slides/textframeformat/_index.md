---
title: TextFrameFormat
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: شامل ویژگی‌های formatTextFrameFormatting فریم‌های متن است.
type: docs
url: /fa/com.aspose.slides/textframeformat/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

حاوی ویژگی‌های formatTextFrameFormatting متن فریم است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | یک نمونه جدید از کلاس [TextFrameFormat](../../com.aspose.slides/textframeformat) ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | سبک متن را بازمی‌گرداند. |
| [getThreeDFormat()](#getThreeDFormat--) | شی ThreeDFormat را که ویژگی‌های اثر سه‌بعدی متن را نشان می‌دهد بازمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالا (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالا (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایین (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایین (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [getWrapText()](#getWrapText--) | True اگر متن در حاشیه‌های TextFrame بسته شود. |
| [setWrapText(byte value)](#setWrapText-byte-) | True اگر متن در حاشیه‌های TextFrame بسته شود. |
| [getAnchoringType()](#getAnchoringType--) | متن عمودی لنگر را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | متن عمودی لنگر را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. |
| [getCenterText()](#getCenterText--) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. |
| [setCenterText(byte value)](#setCenterText-byte-) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را تعیین می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | جهت متن را تعیین می‌کند. |
| [getAutofitType()](#getAutofitType--) | حالت autofit متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | حالت autofit متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setColumnCount(int value)](#setColumnCount-int-) | تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getColumnSpacing()](#getColumnSpacing--) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. |
| [getRotationAngle()](#getRotationAngle--) | چرخش سفارشی اعمال‌شده به متن داخل جعبه مرزی را مشخص می‌کند. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | چرخش سفارشی اعمال‌شده به متن داخل جعبه مرزی را مشخص می‌کند. |
| [getTransform()](#getTransform--) | شکل پیچ‌گرداندن متن را دریافت یا تنظیم می‌کند. |
| [setTransform(byte value)](#setTransform-byte-) | شکل پیچ‌گرداندن متن را دریافت یا تنظیم می‌کند. |
| [getKeepTextFlat()](#getKeepTextFlat--) | نگه‌داشتن متن صاف حتی اگر اثر چرخش سه‌بعدی اعمال شده باشد را دریافت یا تنظیم می‌کند. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | نگه‌داشتن متن صاف حتی اگر اثر چرخش سه‌بعدی اعمال شده باشد را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر فریم متن را با استفاده از وراثت دریافت می‌کند. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


یک نمونه جدید از کلاس [TextFrameFormat](../../com.aspose.slides/textframeformat) ایجاد می‌کند.

### getVersion() {#getVersion--}
```
public long getVersion()
```


نسخه. فقط-قابل-خواندن long.

**بازگشت:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


سبک متن را بازمی‌گرداند. فقط-قابل-خواندن [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگشت:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


شی ThreeDFormat را که ویژگی‌های اثر سه‌بعدی متن را نشان می‌دهد بازمی‌گرداند. فقط-قابل-خواندن [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // تنظیم تبدیل متن
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // تنظیم برآمدگی
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // تنظیم کانتور
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // تنظیم عمق
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // تنظیم ماده
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // تنظیم نورپردازی
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // تنظیم نوع دوربین
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


حاشیه چپ (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**بازگشت:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


حاشیه چپ (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


حاشیه راست (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**بازگشت:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


حاشیه راست (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


حاشیه بالا (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**بازگشت:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


حاشیه بالا (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


حاشیه پایین (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**بازگشت:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


حاشیه پایین (نقطه) را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


True اگر متن در حاشیه‌های TextFrame بسته شود. قابل‌خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

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

**بازگشت:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


True اگر متن در حاشیه‌های TextFrame بسته شود. قابل‌خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


متن عمودی لنگر را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


متن عمودی لنگر را در یک TextFrame بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. قابل‌خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. قابل‌خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


جهت متن را تعیین می‌کند. مقدار حاصل از چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle خلاصه می‌شود. قابل‌خواندن/نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


جهت متن را تعیین می‌کند. مقدار حاصل از چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle خلاصه می‌شود. قابل‌خواندن/نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


حالت autofit متن را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**بازگشت:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


حالت autofit متن را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار صفر تنظیم می‌شود. مقدار 0 به معنای مقدار تعریف‌نشده است. قابل‌خواندن/نوشتن int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
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

**بازگشت:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار صفر تنظیم می‌شود. مقدار 0 به معنای مقدار تعریف‌نشده است. قابل‌خواندن/نوشتن int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. این مقدار فقط زمانی که بیش از یک ستون موجود باشد اعمال می‌شود. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار صفر تنظیم می‌شود. قابل‌خواندن/نوشتن double.

**بازگشت:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. این مقدار فقط زمانی که بیش از یک ستون موجود باشد اعمال می‌شود. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار صفر تنظیم می‌شود. قابل‌خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


چرخش سفارشی اعمال‌شده به متن داخل جعبه مرزی را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش مستقل از شکل اعمال می‌شود؛ یعنی شکل می‌تواند چرخش داشته باشد علاوه بر چرخش متن. مقدار حاصل از چرخش بصری متن که از این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType خلاصه می‌شود. قابل‌خواندن/نوشتن float.

--------------------

> ```
> موردی را در نظر بگیرید که یک شکل چرخش 90 درجه ساعت‌گرد بر آن اعمال شده است. 
>  علاوه بر این، خود متن چرخش -90 درجه پاد ساعت‌گرد دارد 
>  پاد ساعت‌گرد بر آن اعمال شده است. سپس شکل حاصل به نظر می‌رسد که
>  چرخیده باشد اما متن داخل آن به نظر می‌رسد که اصلاً چرخیده نشده است.
```

**بازگشت:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


چرخش سفارشی اعمال‌شده به متن داخل جعبه مرزی را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش مستقل از شکل اعمال می‌شود؛ یعنی شکل می‌تواند چرخش داشته باشد علاوه بر چرخش متن. مقدار حاصل از چرخش بصری متن که از این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType خلاصه می‌شود. قابل‌خواندن/نوشتن float.

--------------------

> ```
> موردی را در نظر بگیرید که یک شکل چرخش 90 درجه ساعت‌گرد بر آن اعمال شده است. 
>  علاوه بر این، خود بدنه متن چرخش -90 درجه پاد ساعت‌گرد دارد 
>  پاد ساعت‌گرد بر آن اعمال شده است. سپس شکل حاصل به نظر می‌رسد که
>  چرخیده باشد اما متن داخل آن به نظر می‌رسد که اصلاً چرخیده نشده باشد.
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


شکل پیچ‌گرداندن متن را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [TextShapeType](../../com.aspose.slides/textshapetype).

**بازگشت:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


شکل پیچ‌گرداندن متن را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [TextShapeType](../../com.aspose.slides/textshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


نگه‌داشتن متن صاف حتی اگر اثر چرخش سه‌بعدی اعمال شده باشد را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


نگه‌داشتن متن صاف حتی اگر اثر چرخش سه‌بعدی اعمال شده باشد را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


داده‌های قالب‌بندی مؤثر فریم متن را با استفاده از وراثت دریافت می‌کند.

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

**بازگشت:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - یک [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).