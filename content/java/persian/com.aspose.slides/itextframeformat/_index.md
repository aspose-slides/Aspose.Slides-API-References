---
title: ITextFrameFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: حاوی ویژگی‌های قالب‌بندی TextFrames است.
type: docs
url: /fa/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

حاوی ویژگی‌های قالب‌بندی TextFrame است.
## متدها

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | سبک متن را برمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالا (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالا (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایین (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایین (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. |
| [getWrapText()](#getWrapText--) | در صورتی که متن در حاشیه‌های TextFrame بسته شود، مقدار true. |
| [setWrapText(byte value)](#setWrapText-byte-) | در صورتی که متن در حاشیه‌های TextFrame بسته شود، مقدار true. |
| [getAnchoringType()](#getAnchoringType--) | متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getCenterText()](#getCenterText--) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت یابد. |
| [setCenterText(byte value)](#setCenterText-byte-) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت یابد. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را تعیین می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | جهت متن را تعیین می‌کند. |
| [getAutofitType()](#getAutofitType--) | حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setColumnCount(int value)](#setColumnCount-int-) | تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getColumnSpacing()](#getColumnSpacing--) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را برمی‌گرداند یا تنظیم می‌کند. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را برمی‌گرداند یا تنظیم می‌کند. |
| [getThreeDFormat()](#getThreeDFormat--) | شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک متن را نمایندگی می‌کند، برمی‌گرداند. |
| [getKeepTextFlat()](#getKeepTextFlat--) | حفظ متن خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | حفظ متن خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getRotationAngle()](#getRotationAngle--) | چرخش سفارشی که بر متن داخل جعبه مرزبندی اعمال می‌شود را مشخص می‌کند. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | چرخش سفارشی که بر متن داخل جعبه مرزبندی اعمال می‌شود را مشخص می‌کند. |
| [getTransform()](#getTransform--) | شکل بسته‌بندی متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setTransform(byte value)](#setTransform-byte-) | شکل بسته‌بندی متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر TextFrame را با در نظر گرفتن ارث‌بری برمی‌گرداند. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

سبک متن را برمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

حاشیه چپ (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**بازگرداندن:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

حاشیه چپ (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

حاشیه راست (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**بازگرداندن:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

حاشیه راست (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

حاشیه بالا (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**بازگرداندن:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

حاشیه بالا (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

حاشیه پایین (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**بازگرداندن:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

حاشیه پایین (نقطه) در یک TextFrame را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

در صورتی که متن در حاشیه‌های TextFrame بسته شود، مقدار true. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگرداندن:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

در صورتی که متن در حاشیه‌های TextFrame بسته شود، مقدار true. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگرداندن:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت یابد. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگرداندن:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت یابد. قابل خواندن و نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

جهت متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از این خصوصیت و نوع عمودی پیش‌تعریف‌شده در خصوصیت TextVerticalType جمع‌آوری می‌شود. قابل خواندن و نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگرداندن:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

جهت متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از این خصوصیت و نوع عمودی پیش‌تعریف‌شده در خصوصیت TextVerticalType جمع‌آوری می‌شود. قابل خواندن و نوشتن [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextAutofitType](../../com.aspose.slides/textautofittype).

**بازگرداندن:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextAutofitType](../../com.aspose.slides/textautofittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. این مقدار باید یک عدد مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. مقدار 0 به معنی مقدار تعریف‌نشده است. قابل خواندن و نوشتن int.

**بازگرداندن:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. این مقدار باید یک عدد مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. مقدار 0 به معنی مقدار تعریف‌نشده است. قابل خواندن و نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را برمی‌گرداند یا تنظیم می‌کند. این مقدار فقط زمانی اعمال می‌شود که بیش از یک ستون وجود داشته باشد. این مقدار باید یک عدد مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. قابل خواندن و نوشتن double.

**بازگرداندن:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را برمی‌گرداند یا تنظیم می‌کند. این مقدار فقط زمانی اعمال می‌شود که بیش از یک ستون وجود داشته باشد. این مقدار باید یک عدد مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

شیء ThreeDFormat که ویژگی‌های اثر 3D برای یک متن را نمایندگی می‌کند، برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // تنظیم تبدیل متن
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // تنظیم استخراج
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


**بازگرداندن:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

حفظ متن خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن boolean.

**بازگرداندن:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

حفظ متن خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

چرخش سفارشی که بر متن داخل جعبه مرزبندی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، از چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، به‌صورت مستقل از شکل اعمال می‌شود. یعنی می‌توان چرخش را بر شکل اعمال کرد به‌علاوه چرخش متنی که بر خود متن اعمال می‌شود. مقدار نهایی چرخش بصری متن که از این خصوصیت و نوع عمودی پیش‌تعریف‌شده در خصوصیت TextVerticalType جمع‌آوری می‌شود. قابل خواندن و نوشتن float.

--------------------

> ```
> در نظر بگیرید که یک شکل چرخش 90 درجه ساعت‌گرد بر روی آن اعمال شده است. 
>  علاوه بر این، بدنهٔ متن خودش چرخش -90 درجه پادساعت دارد. 
>  پادساعت بر روی آن اعمال شده است. سپس شکل حاصل به نظر می‌رسد که 
>  چرخانده شده باشد اما متن داخل آن به نظر می‌رسد که اصلاً چرخانده نشده است.
```

**بازگرداندن:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

چرخش سفارشی که بر متن داخل جعبه مرزبندی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، از چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، به‌صورت مستقل از شکل اعمال می‌شود. یعنی می‌توان چرخش را بر شکل اعمال کرد به‌علاوه چرخش متنی که بر خود متن اعمال می‌شود. مقدار نهایی چرخش بصری متن که از این خصوصیت و نوع عمودی پیش‌تعریف‌شده در خصوصیت TextVerticalType جمع‌آوری می‌شود. قابل خواندن و نوشتن float.

--------------------

> ```
> در نظر بگیرید که یک شکل چرخش 90 درجه ساعت‌گرد بر روی آن اعمال شده است. 
>  علاوه بر این، خود بدنهٔ متن چرخش -90 درجه 
>  پادساعت بر روی آن اعمال شده است. سپس شکل حاصل به نظر می‌رسد که
>  چرخانده شده باشد اما متن داخل آن به نظر می‌رسد که اصلاً چرخانده نشده باشد.
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

شکل بسته‌بندی متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextShapeType](../../com.aspose.slides/textshapetype).

**بازگرداندن:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

شکل بسته‌بندی متن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [TextShapeType](../../com.aspose.slides/textshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر TextFrame را با در نظر گرفتن ارث‌بری برمی‌گرداند.

**بازگرداندن:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).