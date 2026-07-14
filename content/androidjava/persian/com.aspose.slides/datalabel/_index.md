---
title: DataLabel
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر برچسب‌های یک سری.
type: docs
url: /fa/com.aspose.slides/datalabel/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

نمایش برچسب‌های سری.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | یک نمونه جدید از کلاس DataLabel ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [isVisible()](#isVisible--) | مقدار False به این معنی است که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show\*-flags (ShowValue, ...) نیز false هستند). |
| [hide()](#hide--) | برچسب داده را با تنظیم همه پرچم‌های Show\*-flags (ShowValue, ...) به حالت false مخفی می‌کند. |
| [getActualLabelText()](#getActualLabelText--) | متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding را با متن پارامتر "text" مقداردهی می‌کند. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | می‌تواند متنی با قالب‌بندی غنی داشته باشد. |
| [getTextFormat()](#getTextFormat--) | قالب متن را برمی‌گرداند. |
| [getX()](#getX--) | مختصات x عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setX(float value)](#setX-float-) | مختصات x عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getY()](#getY--) | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setY(float value)](#setY-float-) | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getWidth()](#getWidth--) | عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(float value)](#setWidth-float-) | عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getRight()](#getRight--) | راست. |
| [getBottom()](#getBottom--) | پایین. |
| [getDataLabelFormat()](#getDataLabelFormat--) | قالب برچسب داده را برمی‌گرداند. |
| [getValueFromCell()](#getValueFromCell--) | سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. |
| [getActualY()](#getActualY--) | بالای واقعی عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد FillFormat را برمی‌گرداند. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```


یک نمونه جدید از کلاس DataLabel ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint ‎والد. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شی Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


مقدار False به این معنی است که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show\*-flags (ShowValue, ...) نیز false هستند). فقط-خواندنی  boolean .

اگر برچسب داده قابل مشاهده باشد می‌توانید آن را با متد Hide() مخفی کنید. اما اگر برچسب داده قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید با تنظیم پرچم‌های Show\*-flags (ShowValue, ...) به حالت true برچسب داده را قابل مشاهده کنید.

**بازگشت:**
boolean
### hide() {#hide--}
```
public final void hide()
```


برچسب داده را با تنظیم همه پرچم‌های Show\*-flags (ShowValue, ...) به حالت false مخفی می‌کند. پس از این IsVisible برابر false خواهد بود.

اگر برچسب داده قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید با تنظیم پرچم‌های Show\*-flags (ShowValue, ...) به حالت true برچسب داده را قابل مشاهده کنید.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```


متن واقعی برچسب را بر اساس تنظیمات DataLabelFormat یا مقدار TextFrameForOverriding.Text برمی‌گرداند.

**بازگشت:**
java.lang.String - شیء java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


TextFrameForOverriding را با متن پارامتر "text" مقداردهی می‌کند. اگر TextFrameForOverriding از پیش مقداردهی شده باشد، به سادگی متن آن را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای یک TextFrameForOverriding جدید. |

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


می‌تواند متنی با قالب‌بندی غنی داشته باشد. اگر این ویژگی null نباشد، مقدار متن قالب‌بندی‌شده آن متن تولید خودکار برچسب داده را بازنویسی می‌کند. متن تولید خودکار برچسب داده به معنای متنی است که توسط ویژگی‌های ShowSeriesName، ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


قالب متن را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگشت:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```


مختصات x را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**بازگشت:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


مختصات x را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```


مختصات y را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**بازگشت:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


مختصات y را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```


عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**بازگشت:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**بازگشت:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```


راست. فقط-خواندنی  float .

**بازگشت:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


پایین. فقط-خواندنی  float .

**بازگشت:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```


قالب برچسب داده را برمی‌گرداند. فقط-خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازگشت:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```


سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد، اعمال می‌شود.

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```


سلول داده کتاب کار را می‌گیرد یا تنظیم می‌کند. در صورتی که ویژگی IDataLabelFormat.ShowLabelValueFromCell برابر true باشد، اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```


موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط  float .

**بازگشت:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


موقعیت واقعی بالای عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط  float .

**بازگشت:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط  float .

**بازگشت:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط  float .

**بازگشت:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


اسلاید والد FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


ارائهٔ والد FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)