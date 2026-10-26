---
title: ChartPlotArea
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مستطیلی که نمودار باید در آن ترسیم شود.
type: docs
url: /fa/com.aspose.slides/chartplotarea/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

نمایشی از مستطیلی که نمودار باید در آن ترسیم شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getFormat()](#getFormat--) | قالب ناحیهٔ نمودار را برمی‌گرداند. |
| [getX()](#getX--) | مختصات x گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [setX(float value)](#setX-float-) | مختصات x گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [getY()](#getY--) | مختصات y گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [setY(float value)](#setY-float-) | مختصات y گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [getWidth()](#getWidth--) | عرض جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(float value)](#setWidth-float-) | عرض جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. |
| [getRight()](#getRight--) | راست. |
| [getBottom()](#getBottom--) | پایین. |
| [getChart()](#getChart--) | نمودار. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | نحوهٔ محاسبه مکان را تعریف می‌کند: true – به‌صورت خودکار محاسبه می‌شود؛ توسط ویژگی‌های X، Y، Width، Height تعریف می‌شود. |
| [getLayoutTargetType()](#getLayoutTargetType--) | اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند آیا ناحیهٔ نمودار بر اساس داخل آن (بدون محورها و برچسب‌های محورها) یا خارج آن (شامل محورها و برچسب‌های محورها) چیدمان شود. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند آیا ناحیهٔ نمودار بر основе داخل آن (بدون محورها و برچسب‌های محورها) یا خارج آن (شامل محورها و برچسب‌های محورها) چیدمان شود. |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. |
| [getActualY()](#getActualY--) | بالای واقعی عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد FillFormat را برمی‌گرداند. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

قالب ناحیهٔ نمودار را برمی‌گرداند. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### getX() {#getX--}
```
public final float getX()
```

مختصات x گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

مختصات x گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

مختصات y گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

مختصات y گوشهٔ چپ-بالای جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

عرض جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

عرض جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

ارتفاع جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

ارتفاع جعبهٔ محصور ناحیهٔ نمودار را به عنوان کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

راست. فقط خواندنی float.

**بازگشت:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

پایین. فقط خواندنی float.

**بازگشت:**
float
### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار. فقط خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)
### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

نحوهٔ محاسبه مکان را تعریف می‌کند: true – به‌صورت خودکار محاسبه می‌شود؛ توسط ویژگی‌های X، Y، Width، Height تعریف می‌شود. فقط خواندنی boolean.

**بازگشت:**
boolean
### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند آیا ناحیهٔ نمودار بر اساس داخل آن (بدون محورها و برچسب‌های محورها) یا خارج آن (شامل محورها و برچسب‌های محورها) چیدمان شود. خواندنی/نوشتنی [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**بازگشت:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند آیا ناحیهٔ نمودار بر اساس داخل آن (بدون محورها و برچسب‌های محورها) یا خارج آن (شامل محورها و برچسب‌های محورها) چیدمان شود. خواندنی/نوشتنی [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی float.

**بازگشت:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

بالای واقعی عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی float.

**بازگشت:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی float.

**بازگشت:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی float.

**بازگشت:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد FillFormat را برمی‌گرداند. فقط خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد FillFormat را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)