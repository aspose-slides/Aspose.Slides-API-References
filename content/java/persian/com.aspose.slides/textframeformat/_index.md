---
title: TextFrameFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: شامل ویژگی‌های formatTextFrameFormatting متن‌قاب‌ها است.
type: docs
url: /fa/com.aspose.slides/textframeformat/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)  
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

شامل ویژگی‌های formatTextFrameFormatting متن‌قاب است.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | یک نمونه جدید از کلاس [TextFrameFormat](../../com.aspose.slides/textframeformat) را مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | سبک متن را بازمی‌گرداند. |
| [getThreeDFormat()](#getThreeDFormat--) | شیء ThreeDFormat را بازمی‌گرداند که ویژگی‌های اثر 3d برای متن را نمایان می‌کند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالا (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالا (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایین (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایین (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getWrapText()](#getWrapText--) | True اگر متن در حاشیه‌های TextFrame بسته شود. |
| [setWrapText(byte value)](#setWrapText-byte-) | True اگر متن در حاشیه‌های TextFrame بسته شود. |
| [getAnchoringType()](#getAnchoringType--) | متن مرسأ عمودی در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | متن مرسأ عمودی در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. |
| [getCenterText()](#getCenterText--) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. |
| [setCenterText(byte value)](#setCenterText-byte-) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را تعیین می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | جهت متن را تعیین می‌کند. |
| [getAutofitType()](#getAutofitType--) | حالت Autofit متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | حالت Autofit متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [setColumnCount(int value)](#setColumnCount-int-) | تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. |
| [getColumnSpacing()](#getColumnSpacing--) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. |
| [getRotationAngle()](#getRotationAngle--) | چرخش سفارشی‌ای که بر روی متن در داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | چرخش سفارشی‌ای که بر روی متن در داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. |
| [getTransform()](#getTransform--) | شکل بسته‌بندی متن را دریافت یا تنظیم می‌کند. |
| [setTransform(byte value)](#setTransform-byte-) | شکل بسته‌بندی متن را دریافت یا تنظیم می‌کند. |
| [getKeepTextFlat()](#getKeepTextFlat--) | حفظ مسطح بودن متن حتی در صورت اعمال اثر چرخش 3-D را دریافت یا تنظیم می‌کند. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | حفظ مسطح بودن متن حتی در صورت اعمال اثر چرخش 3-D را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | داده‌های فرمت‌بندی موثر قاب متن را با وراثت اعمال‌شده دریافت می‌کند. |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

یک نمونه جدید از کلاس [TextFrameFormat](../../com.aspose.slides/textframeformat) را مقداردهی اولیه می‌کند.

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گردد:**
long

### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

سبک متن را بازمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازمی‌گردد:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

شیء ThreeDFormat را بازمی‌گرداند که ویژگی‌های اثر 3d برای متن را نمایان می‌کند. فقط-خواندنی [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // تنظیم تبدیل متن
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // تنظیم اکستروژن
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // تنظیم کانتور
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // تنظیم عمق
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // تنظیم مواد
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


**بازمی‌گردد:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

حاشیه چپ (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازمی‌گردد:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

حاشیه چپ (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

حاشیه راست (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازمی‌گردد:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

حاشیه راست (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

حاشیه بالا (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازمی‌گردد:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

حاشیه بالا (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

حاشیه پایین (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازمی‌گردد:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

حاشیه پایین (نقطه) در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True اگر متن در حاشیه‌های TextFrame بسته شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

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


**بازمی‌گردد:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

True اگر متن در حاشیه‌های TextFrame بسته شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> کد نمونه زیر نشان می‌دهد چگونه متن را در Presentation بسته‌بندی کنیم.
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

متن مرسأ عمودی در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازمی‌گردد:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

متن مرسأ عمودی در TextFrame را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازمی‌گردد:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

جهت متن را تعیین می‌کند. مقدار حاصل از چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle جمع‌بندی می‌شود. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازمی‌گردد:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

جهت متن را تعیین می‌کند. مقدار حاصل از چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle جمع‌بندی می‌شود. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

حالت Autofit متن را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
>  کد نمونه زیر نشان می‌دهد چگونه شکل را برای متناسب کردن متن در یک ارائهٔ پاورپوینت تغییر اندازه دهیم.
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
>  کد نمونه زیر نشان می‌دهد چگونه متن را در هنگام سرریز کاهش دهیم.
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


**بازمی‌گردد:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

حالت Autofit متن را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

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

تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار به صفر تنظیم می‌شود. مقدار 0 نشانگر مقدار نامشخص است. خواندنی/نوشتنی int.

--------------------

> ```
> کد نمونه زیر نشان می‌دهد چگونه ستون‌ها را در قاب متن داخل یک ارائهٔ پاورپوینت اضافه کنیم.
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


**بازمی‌گردد:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

تعداد ستون‌ها در ناحیه متن را بازمی‌گرداند یا تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار به صفر تنظیم می‌شود. مقدار 0 نشانگر مقدار نامشخص است. خواندنی/نوشتنی int.

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

فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. این مقدار تنها وقتی بیش از یک ستون وجود داشته باشد اعمال می‌شود. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار به صفر تنظیم می‌شود. خواندنی/نوشتنی double.

**بازمی‌گردد:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را بازمی‌گرداند یا تنظیم می‌کند. این مقدار تنها وقتی بیش از یک ستون وجود داشته باشد اعمال می‌شود. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار به صفر تنظیم می‌شود. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

چرخش سفارشی‌ای که بر روی متن در داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش به صورت مستقل از شکل اعمال می‌شود؛ یعنی شکل می‌تواند چرخش داشته باشد در حالی که متن خود چرخش جداگانه‌ای داشته باشد. مقدار حاصل از چرخش بصری متن که از این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType جمع‌بندی می‌شود. خواندنی/نوشتنی float.

--------------------

> ```
> در نظر بگیرید که یک شکل چرخش 90 درجه ساعتگرد بر روی آن اعمال شده است. 
>  علاوه بر این، بدنهٔ متن خود نیز چرخش -90 درجه ضد ساعتگرد داشته است. 
>  سپس شکل حاصل به نظر می‌رسد چرخیده باشد، اما متن داخل آن طوری به نظر می‌رسد که اصلاً چرخیده نشده باشد.
> ```

**بازمی‌گردد:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

چرخش سفارشی‌ای که بر روی متن در داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش به صورت مستقل از شکل اعمال می‌شود؛ یعنی شکل می‌تواند چرخش داشته باشد در حالی که متن خود چرخش جداگانه‌ای داشته باشد. مقدار حاصل از چرخش بصری متن که از این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType جمع‌بندی می‌شود. خواندنی/نوشتنی float.

--------------------

> ```
> در نظر بگیرید که یک شکل دارای چرخش 90 درجه ساعتگرد است. 
>  به علاوه، بدنهٔ متن خود نیز چرخش -90 درجه ضد ساعتگرد دارد. 
>  سپس شکل حاصل به نظر می‌رسد چرخیده باشد، اما 
>  متن داخل آن طوری به نظر می‌رسد که گویی هیچ‌گاه چرخیده نشده باشد.
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

شکل بسته‌بندی متن را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [TextShapeType](../../com.aspose.slides/textshapetype).

**بازمی‌گردد:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

شکل بسته‌بندی متن را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [TextShapeType](../../com.aspose.slides/textshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

حفظ مسطح بودن متن حتی در صورت اعمال اثر چرخش 3-D را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی boolean.

**بازمی‌گردد:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

حفظ مسطح بودن متن حتی در صورت اعمال اثر چرخش 3-D را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

داده‌های فرمت‌بندی موثر قاب متن را با وراثت اعمال‌شده دریافت می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد که چگونه برخی از ویژگی‌های مؤثر فرمت‌بندی قاب متن را دریافت کنید.
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


**بازمی‌گردد:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - یک [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).