---
title: IDataLabel
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر برچسب‌های یک سری است.
type: docs
url: /fa/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

نمایانگر برچسب‌های یک سری است.
## متدها

| متد | توضیح |
| --- | --- |
| [isVisible()](#isVisible--) | False به این معناست که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show*-flags (ShowValue, ...) نیز False هستند). |
| [hide()](#hide--) | برچسب داده را با تنظیم تمام پرچم‌های Show*-flags (ShowValue, ...) به حالت false مخفی می‌کند. |
| [getDataLabelFormat()](#getDataLabelFormat--) | قالب برچسب داده را برمی‌گرداند. |
| [getValueFromCell()](#getValueFromCell--) | دریافت یا تنظیم سلول داده کتاب کار. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | دریافت یا تنظیم سلول داده کتاب کار. |
| [getActualLabelText()](#getActualLabelText--) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False به این معناست که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show*-flags (ShowValue, ...) نیز False هستند). فقط‌خواندنی boolean.

--------------------

اگر برچسب داده قابل مشاهده باشد می‌توانید آن را با متد Hide() مخفی کنید. اما اگر برچسب داده قابل مشاهده نباشد (IsVisible برابر False) می‌توانید با تنظیم پرچم‌های Show*-flags (ShowValue, ...) به حالت true، برچسب را مشاهده‌پذیر کنید.

**بازگشت:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


برچسب داده را با تنظیم تمام پرچم‌های Show*-flags (ShowValue, ...) به حالت false مخفی می‌کند. بعد از این IsVisible برابر False خواهد بود.

--------------------

اگر برچسب داده قابل مشاهده نباشد (IsVisible برابر False) می‌توانید با تنظیم پرچم‌های Show*-flags (ShowValue, ...) به حالت true، برچسب را مشاهده‌پذیر کنید.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


قالب برچسب داده را برمی‌گرداند. فقط‌خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازگشت:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


دریافت یا تنظیم سلول داده کتاب کار. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود.

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


دریافت یا تنظیم سلول داده کتاب کار. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند.

**بازگشت:**
java.lang.String - Actual label text String