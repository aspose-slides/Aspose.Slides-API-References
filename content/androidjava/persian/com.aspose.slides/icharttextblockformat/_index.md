---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /fa/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

خواص قالب‌بندی برای عناصر متن نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | مقدار یا تنظیم متن لنگر عمودی در یک TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | مقدار یا تنظیم متن لنگر عمودی در یک TextFrame. |
| [getCenterText()](#getCenterText--) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. |
| [setCenterText(byte value)](#setCenterText-byte-) | اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. |
| [getTextVerticalType()](#getTextVerticalType--) | جهت متن را تعیین می‌کند. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | جهت متن را تعیین می‌کند. |
| [getMarginLeft()](#getMarginLeft--) | مقدار یا تنظیم حاشیه چپ (نقطه) در یک TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | مقدار یا تنظیم حاشیه چپ (نقطه) در یک TextFrame. |
| [getMarginRight()](#getMarginRight--) | مقدار یا تنظیم حاشیه راست (نقطه) در یک TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | مقدار یا تنظیم حاشیه راست (نقطه) در یک TextFrame. |
| [getMarginTop()](#getMarginTop--) | مقدار یا تنظیم حاشیه بالا (نقطه) در یک TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | مقدار یا تنظیم حاشیه بالا (نقطه) در یک TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | مقدار یا تنظیم حاشیه پایین (نقطه) در یک TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | مقدار یا تنظیم حاشیه پایین (نقطه) در یک TextFrame. |
| [getWrapText()](#getWrapText--) | True اگر متن در حاشیه‌های TextFrame پیچیده شود. |
| [setWrapText(byte value)](#setWrapText-byte-) | True اگر متن در حاشیه‌های TextFrame پیچیده شود. |
| [getAutofitType()](#getAutofitType--) | مقدار یا تنظیم حالت autofit متن. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | مقدار یا تنظیم حالت autofit متن. |
| [getRotationAngle()](#getRotationAngle--) | چرخش سفارشی اعمال‌شده به متن در داخل جعبه محدود‌کننده را تعیین می‌کند. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | چرخش سفارشی اعمال‌شده به متن در داخل جعبه محدود‌کننده را تعیین می‌کند. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


مقدار یا تنظیم متن لنگر عمودی در یک TextFrame. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**بازگشت:**
`byte`
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


مقدار یا تنظیم متن لنگر عمودی در یک TextFrame. خواندنی/نوشتنی [TextAnchorType](../../com.aspose.slides/textanchortype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `byte` |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
`byte`
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


اگر NullableBool.True باشد، متن باید به صورت افقی در جعبه مرکز شود. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `byte` |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


جهت متن را تعیین می‌کند. مقدار حاصل از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به‌دست می‌آید. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**بازگشت:**
`byte`
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


جهت متن را تعیین می‌کند. مقدار حاصل از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به‌دست می‌آید. خواندنی/نوشتنی [TextVerticalType](../../com.aspose.slides/textverticaltype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `byte` |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


مقدار یا تنظیم حاشیه چپ (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**بازگشت:**
`double`
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


مقدار یا تنظیم حاشیه چپ (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `double` |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


مقدار یا تنظیم حاشیه راست (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**بازگشت:**
`double`
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


مقدار یا تنظیم حاشیه راست (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `double` |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


مقدار یا تنظیم حاشیه بالا (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**بازگشت:**
`double`
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


مقدار یا تنظیم حاشیه بالا (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `double` |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


مقدار یا تنظیم حاشیه پایین (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**بازگشت:**
`double`
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


مقدار یا تنظیم حاشیه پایین (نقطه) در یک TextFrame. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی `double`.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `double` |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


True اگر متن در حاشیه‌های TextFrame پیچیده شود. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2007/2013). خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
`byte`
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


True اگر متن در حاشیه‌های TextFrame پیچیده شود. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2007/2013). خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `byte` |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


مقدار یا تنظیم حالت autofit متن. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**بازگشت:**
`byte`
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


مقدار یا تنظیم حالت autofit متن. تغییر این ویژگی می‌تواند فقط بر روی این بخش‌های نمودار تأثیر بگذارد: DataLabel و DataLabelFormat (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ تأثیری بر رندر ندارد). خواندنی/نوشتنی [TextAutofitType](../../com.aspose.slides/textautofittype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `byte` |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


چرخش سفارشی اعمال‌شده به متن در داخل جعبه محدود‌کننده را تعیین می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخش داشته باشد به‌علاوه اینکه متن خود نیز چرخش داشته باشد. مقدار حاصل از ترکیب این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType به‌دست می‌آید. خواندنی/نوشتنی `float`.

--------------------

> ```
> در نظر بگیرید که یک شکل چرخش 90 درجه ساعتگرد به آن اعمال شده است. 
>  علاوه بر این، خود بدنه متن چرخش -90 درجه 
>  پادساعتگرد به آن اعمال شده است. سپس شکل حاصل به نظر می‌رسد که
>  چرخانده شده باشد، اما متن داخل آن به گونه‌ای ظاهر می‌شود که انگار اصلاً چرخانده نشده است.
> ```


**بازگشت:**
`float`
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


چرخش سفارشی اعمال‌شده به متن در داخل جعبه محدود‌کننده را تعیین می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، این چرخش مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخش داشته باشد به‌علاوه اینکه متن خود نیز چرخش داشته باشد. مقدار حاصل از ترکیب این ویژگی و نوع عمودی پیش‌تعریف‌شده در ویژگی TextVerticalType به‌دست می‌آید. خواندنی/نوشتنی `float`.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | `float` |  |