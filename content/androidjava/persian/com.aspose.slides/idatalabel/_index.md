---
title: IDataLabel
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش برچسب‌های یک سری.
type: docs
url: /fa/com.aspose.slides/idatalabel/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

نمایش برچسب‌های یک سری.
## متدها

| متد | توضیح |
| --- | --- |
| [isVisible()](#isVisible--) | False به این معنی است که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show*-flags (ShowValue, ...) نادرست هستند). |
| [hide()](#hide--) | پنهان کردن برچسب داده با تنظیم تمام پرچم‌های Show*-flags (ShowValue, ...) به حالت نادرست. |
| [getDataLabelFormat()](#getDataLabelFormat--) | قالب برچسب داده را باز می‌گرداند. |
| [getValueFromCell()](#getValueFromCell--) | سلول دادهٔ دفترکار را دریافت یا تنظیم می‌کند. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | سلول دادهٔ دفترکار را دریافت یا تنظیم می‌کند. |
| [getActualLabelText()](#getActualLabelText--) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text بر می‌گرداند. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False به این معنی است که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show*-flags (ShowValue, ...) نادرست هستند). فقط-خواندنی boolean.

--------------------

اگر برچسب داده قابل مشاهده باشد می‌توانید با متد Hide() آن را پنهان کنید. اما اگر برچسب داده قابل مشاهده نباشد (IsVisible نادرست است) می‌توانید با تنظیم پرچم‌های Show*-flags (ShowValue, ...) به حالت درست، برچسب داده را قابل مشاهده کنید.

**باز می‌گرداند:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

پنهان کردن برچسب داده با تنظیم تمام پرچم‌های Show*-flags (ShowValue, ...) به حالت نادرست. بعد از این IsVisible نادرست خواهد بود.

--------------------

اگر برچسب داده قابل مشاهده نباشد (IsVisible نادرست است) می‌توانید با تنظیم پرچم‌های Show*-flags (ShowValue, ...) به حالت درست، برچسب داده را قابل مشاهده کنید.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

قالب برچسب داده را باز می‌گرداند. فقط-خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**باز می‌گرداند:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

سلول دادهٔ دفترکار را دریافت یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود.

**باز می‌گرداند:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

سلول دادهٔ دفترکار را دریافت یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text بر می‌گرداند.

**باز می‌گرداند:**
java.lang.String - متن برچسب واقعی