---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /fa/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی مؤثر قاب متن را شامل می‌شود.

--------------------

این رابط همراه با رابط [ITextFrameFormat](../../com.aspose.slides/itextframeformat) برای بازگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## Methods

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | استایل مؤثر متن را بازمی‌گرداند. |
| [getMarginLeft()](#getMarginLeft--) | حاشیه چپ (نقطه) در یک TextFrame را بازمی‌گرداند. |
| [getMarginRight()](#getMarginRight--) | حاشیه راست (نقطه) در یک TextFrame را بازمی‌گرداند. |
| [getMarginTop()](#getMarginTop--) | حاشیه بالایی (نقطه) در یک TextFrame را بازمی‌گرداند. |
| [getMarginBottom()](#getMarginBottom--) | حاشیه پایینی (نقطه) در یک TextFrame را بازمی‌گرداند. |
| [getWrapText()](#getWrapText--) | بازمی‌گرداند که آیا متن در حاشیه‌های TextFrame پیچیده شده است. |
| [getAnchoringType()](#getAnchoringType--) | متن لنگر عمودی را در یک TextFrame بازمی‌گرداند. |
| [getCenterText()](#getCenterText--) | بازمی‌گرداند که آیا متن باید به‌صورت افقی در جعبه مرکز شود. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را بازمی‌گرداند. |
| [getAutofitType()](#getAutofitType--) | حالت خودکار تنظیم متن را بازمی‌گرداند. |
| [getColumnCount()](#getColumnCount--) | تعداد ستون‌های متن در مستطیل محاطی را مشخص می‌کند. |
| [getColumnSpacing()](#getColumnSpacing--) | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را مشخص می‌کند. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


استایل مؤثر متن را بازمی‌گرداند. فقط-خواندنی [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**بازمی‌گرداند:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


حاشیه چپ (نقطه) در یک TextFrame را بازمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


حاشیه راست (نقطه) در یک TextFrame را بازمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


حاشیه بالایی (نقطه) در یک TextFrame را بازمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


حاشیه پایینی (نقطه) در یک TextFrame را بازمی‌گرداند. فقط-خواندنی double.

**بازمی‌گرداند:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


بازمی‌گرداند که آیا متن در حاشیه‌های TextFrame پیچیده شده است. فقط-خواندنی boolean.

**بازمی‌گرداند:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


متن لنگر عمودی را در یک TextFrame بازمی‌گرداند. فقط-خواندنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازمی‌گرداند:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


بازمی‌گرداند که آیا متن باید به‌صورت افقی در جعبه مرکز شود. فقط-خواندنی boolean.

**بازمی‌گرداند:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


جهت متن را بازمی‌گرداند. فقط-خواندنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازمی‌گرداند:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


حالت خودکار تنظیم متن را بازمی‌گرداند. فقط-خواندنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**بازمی‌گرداند:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


تعداد ستون‌های متن در مستطیل محاطی را مشخص می‌کند. فقط-خواندنی int.

**بازمی‌گرداند:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را مشخص می‌کند. فقط-خواندنی float.

**بازمی‌گرداند:**
float