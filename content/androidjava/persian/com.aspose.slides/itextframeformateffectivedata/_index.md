---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر قاب متن است.
type: docs
url: /fa/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر قاب متن است.

--------------------

این اینترفیس همراه با اینترفیس [ITextFrameFormat](../../com.aspose.slides/itextframeformat) برای برگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | استایل مؤثر متن را بازمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ (نقطه) را در یک TextFrame برمی‌گرداند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست (نقطه) را در یک TextFrame برمی‌گرداند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالایی (نقطه) را در یک TextFrame برمی‌گرداند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایینی (نقطه) را در یک TextFrame برمی‌گرداند. |
| [getWrapText()](#getWrapText--) | برمی‌گرداند که آیا متن در حاشیه‌های TextFrame پیچیده شده است. |
| [getAnchoringType()](#getAnchoringType--) | متن لنگر عمودی را در یک TextFrame بازمی‌گرداند. |
| [getCenterText()](#getCenterText--) | برمی‌گرداند که آیا متن باید به صورت افقی در جعبه مرکز شود. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را بازمی‌گرداند. |
| [getAutofitType()](#getAutofitType--) | حالت تنظیم خودکار متن را بازمی‌گرداند. |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌های متن در مستطیل محاط را مشخص می‌کند. |
| [getColumnSpacing()](#getColumnSpacing--) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را مشخص می‌کند. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

استایل مؤثر متن را بازمی‌گرداند. فقط‌خواندنی [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**بازگشت:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

حاشیه چپ (نقطه) را در یک TextFrame برمی‌گرداند. فقط‌خواندنی double.

**بازگشت:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

حاشیه راست (نقطه) را در یک TextFrame برمی‌گرداند. فقط‌خواندنی double.

**بازگشت:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

حاشیه بالایی (نقطه) را در یک TextFrame برمی‌گرداند. فقط‌خواندنی double.

**بازگشت:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

حاشیه پایینی (نقطه) را در یک TextFrame برمی‌گرداند. فقط‌خواندنی double.

**بازگشت:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

برمی‌گرداند که آیا متن در حاشیه‌های TextFrame پیچیده شده است. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

متن لنگر عمودی را در یک TextFrame بازمی‌گرداند. فقط‌خواندنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

برمی‌گرداند که آیا متن باید به صورت افقی در جعبه مرکز شود. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

جهت متن را بازمی‌گرداند. فقط‌خواندنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

حالت تنظیم خودکار متن را بازمی‌گرداند. فقط‌خواندنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**بازگشت:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

تعداد ستون‌های متن در مستطیل محاط را مشخص می‌کند. فقط‌خواندنی int.

**بازگشت:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را مشخص می‌کند. فقط‌خواندنی float.

**بازگشت:**
float