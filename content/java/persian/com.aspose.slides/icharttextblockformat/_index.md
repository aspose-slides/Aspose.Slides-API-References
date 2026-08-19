---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: نمای�� ویژگی‌های قالب‌بندی برای عناصر متن نمودار.
type: docs
url: /fa/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

نمایش ویژگی‌های قالب‌بندی برای عناصر متن نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getCenterText()](#getCenterText--) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه وسط‌چین شود. |
| [setCenterText(byte value)](#setCenterText-byte-) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه وسط‌چین شود. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را تعیین می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | جهت متن را تعیین می‌کند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | حاشیه چپ (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginRight(double value)](#setMarginRight-double-) | حاشیه راست (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالایی (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginTop(double value)](#setMarginTop-double-) | حاشیه بالایی (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایین (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | حاشیه پایین (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. |
| [getWrapText()](#getWrapText--) | اگر متن در حاشیه‌های TextFrame بسته شود، مقدار true. |
| [setWrapText(byte value)](#setWrapText-byte-) | اگر متن در حاشیه‌های TextFrame بسته شود، مقدار true. |
| [getAutofitType()](#getAutofitType--) | حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. |
| [getRotationAngle()](#getRotationAngle--) | چرخش سفارشی که بر متن داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | چرخش سفارشی که بر متن داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

متن لنگر عمودی را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه وسط‌چین شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه وسط‌چین شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

جهت متن را تعیین می‌کند. مقدار حاصل از چرخش بصری متن که از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به دست می‌آید. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

جهت متن را تعیین می‌کند. مقدار حاصل از چرخش بصری متن که از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به دست می‌آید. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

حاشیه چپ (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

حاشیه چپ (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

حاشیه راست (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

حاشیه راست (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

حاشیه بالایی (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

حاشیه بالایی (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

حاشیه پایین (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**بازگشت:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

حاشیه پایین (نقطه) را در یک TextFrame برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

اگر متن در حاشیه‌های TextFrame بسته شود، مقدار true. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2007/2013). خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

اگر متن در حاشیه‌های TextFrame بسته شود، مقدار true. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2007/2013). خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**بازگشت:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

حالت autofit متن را برمی‌گرداند یا تنظیم می‌کند. تغییر این ویژگی می‌تواند تنها بر این قسمت‌های نمودار تأثیر داشته باشد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

چرخش سفارشی که بر متن داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش به طور مستقل از شکل اعمال می‌گردد. یعنی شکل می‌تواند چرخش داشته باشد در کنار این که متن خودش نیز چرخش داشته باشد. مقدار حاصل از چرخش بصری متن که از ترکیب این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType به دست می‌آید. خواندنی/نوشتنی float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**بازگشت:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

چرخش سفارشی که بر متن داخل جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش به طور مستقل از شکل اعمال می‌گردد. یعنی شکل می‌تواند چرخش داشته باشد در کنار این که متن خودش نیز چرخش داشته باشد. مقدار حاصل از چرخش بصری متن که از ترکیب این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType به دست می‌آید. خواندنی/نوشتنی float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |