---
title: ITextFrameFormat
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: دارای خصوصیات قالب‌بندی TextFrames است.
type: docs
url: /fa/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

دارای خصوصیات قالب‌بندی TextFrame است.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | سبک متن را برمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | مارجین چپ (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | مارجین چپ (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | مارجین راست (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | مارجین راست (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | مارجین بالا (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | مارجین بالا (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | مارجین پایین (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | مارجین پایین (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getWrapText()](#getWrapText--) | اگر متن در حاشیه‌های TextFrame پیچیده شود، True. |
| [setWrapText(byte value)](#setWrapText-byte-) | اگر متن در حاشیه‌های TextFrame پیچیده شود، True. |
| [getAnchoringType()](#getAnchoringType--) | متن لنگر عمودی را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | متن لنگر عمودی را در TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getCenterText()](#getCenterText--) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت داشته باشد. |
| [setCenterText(byte value)](#setCenterText-byte-) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت داشته باشد. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را تعیین می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | جهت متن را تعیین می‌کند. |
| [getAutofitType()](#getAutofitType--) | حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setColumnCount(int value)](#setColumnCount-int-) | تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getColumnSpacing()](#getColumnSpacing--) | فضای بین ستون‌های متن در ناحیه متن (به نقاط) را برمی‌گرداند یا تنظیم می‌کند. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | فضای بین ستون‌های متن در ناحیه متن (به نقاط) را برمی‌گرداند یا تنظیم می‌کند. |
| [getThreeDFormat()](#getThreeDFormat--) | شی ThreeDFormat را که نشانگر ویژگی‌های اثر 3D برای یک متن است، برمی‌گرداند. |
| [getKeepTextFlat()](#getKeepTextFlat--) | حفظ متن به طور کامل خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | حفظ متن به طور کامل خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getRotationAngle()](#getRotationAngle--) | چرخش سفارشی که بر متن داخل جعبه محدود کننده اعمال می‌شود را مشخص می‌کند. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | چرخش سفارشی که بر متن داخل جعبه محدود کننده اعمال می‌شود را مشخص می‌کند. |
| [getTransform()](#getTransform--) | شکل پیچش متن را دریافت یا تنظیم می‌کند. |
| [setTransform(byte value)](#setTransform-byte-) | شکل پیچش متن را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر TextFrame را با به‌کارگیری ارث‌برداری دریافت می‌کند. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

سبک متن را برمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگشت:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

مارجین چپ (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

مارجین چپ (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

مارجین راست (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

مارجین راست (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

مارجین بالا (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

مارجین بالا (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

مارجین پایین (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

مارجین پایین (نقاط) را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

اگر متن در حاشیه‌های TextFrame پیچیده شود، True. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

اگر متن در حاشیه‌های TextFrame پیچیده شود، True. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

متن لنگر عمودی را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

متن لنگر عمودی را در TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت داشته باشد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکزیت داشته باشد. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

جهت متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از این خصوصیت و زاویه سفارشی در خصوصیت RotationAngle جمع می‌شود. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

جهت متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از این خصوصیت و زاویه سفارشی در خصوصیت RotationAngle جمع می‌شود. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**بازگشت:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. مقدار 0 به معنی مقدار نامشخص است. خواندنی/نوشتنی int.

**بازگشت:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

تعداد ستون‌ها در ناحیه متن را برمی‌گرداند یا تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. مقدار 0 به معنی مقدار نامشخص است. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

فضای بین ستون‌های متن در ناحیه متن (به نقاط) را برمی‌گرداند یا تنظیم می‌کند. این مقدار تنها زمانی اعمال می‌شود که بیش از یک ستون موجود باشد. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. خواندنی/نوشتنی double.

**بازگشت:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

فضای بین ستون‌های متن در ناحیه متن (به نقاط) را برمی‌گرداند یا تنظیم می‌کند. این مقدار تنها زمانی اعمال می‌شود که بیش از یک ستون موجود باشد. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

شی ThreeDFormat را که نشانگر ویژگی‌های اثر 3D برای یک متن است، برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // تعیین تبدیل متن
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

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

حفظ متن به طور کامل خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

حفظ متن به طور کامل خارج از صحنه 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

چرخش سفارشی که بر متن داخل جعبه محدود کننده اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، به‌صورت مستقل از شکل اعمال می‌گردد؛ یعنی شکل می‌تواند چرخش داشته باشد در حالی که متن به‌صورت جداگانه نیز چرخش داشته باشد. مقدار نهایی چرخش بصری متن که از این خصوصیت و نوع عمودی پیش‌تعریف‌شده در خصوصیت TextVerticalType جمع می‌شود. خواندنی/نوشتنی float.

--------------------

> ```
> به این حالت فکر کنید که یک شکل دارای چرخش 90 درجه ساعت‌گرد است. 
>  علاوه بر این، متن خود نیز چرخش -90 درجه پاد ساعت‌گرد دارد. 
>  سپس شکل حاصل به نظر می‌رسد چرخیده باشد اما متنی که درون آن است گویی اصلاً چرخیده نشده است. 
```

**بازگشت:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

چرخش سفارشی که بر متن داخل جعبه محدود کننده اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، به‌صورت مستقل از شکل اعمال می‌گردد؛ یعنی شکل می‌تواند چرخش داشته باشد در حالی که متن به‌صورت جداگانه نیز چرخش داشته باشد. مقدار نهایی چرخش بصری متن که از این خصوصیت و نوع عمودی پیش‌تعریف‌شده در خصوصیت TextVerticalType جمع می‌شود. خواندنی/نوشتنی float.

--------------------

> ```
> به این حالت فکر کنید که یک شکل دارای چرخش 90 درجه ساعت‌گرد اعمال شده است. 
>  علاوه بر این، بدنه متن خود نیز دارای چرخش -90 درجه پاد ساعت‌گرد است. 
>  سپس شکل حاصل به نظر می‌رسد که
>  چرخیده باشد اما متن داخل آن گویی اصلاً چرخیده نشده است. 
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

شکل پیچش متن را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [TextShapeType](../../com.aspose.slides/textshapetype).

**بازگشت:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

شکل پیچش متن را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [TextShapeType](../../com.aspose.slides/textshapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر TextFrame را با به‌کارگیری ارث‌برداری دریافت می‌کند.

**بازگشت:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).