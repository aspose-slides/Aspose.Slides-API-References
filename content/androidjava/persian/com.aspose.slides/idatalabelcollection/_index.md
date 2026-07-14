---
title: IDataLabelCollection
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر برچسب‌های یک سری.
type: docs
url: /fa/com.aspose.slides/idatalabelcollection/
---
**تمام واسط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

نمایانگر برچسب‌های یک سری.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برچسب داده را برای نقطه داده‌ای که دارای اندیس مشخص است دریافت می‌کند. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | قالب پیش‌فرض تمام برچسب‌های داده در مجموعه را برمی‌گرداند. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | قالب خطوط راهنمای برچسب‌های داده را نمایان می‌کند. |
| [isVisible()](#isVisible--) | False به این معناست که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر false هستند). |
| [hide()](#hide--) | برچسب داده را به‌صورت پیش‌فرض مخفی کنید با تنظیم تمام پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد کل برچسب‌های داده در مجموعه را دریافت می‌کند. |
| [getParentSeries()](#getParentSeries--) | سری نمودار والد را برمی‌گرداند. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | اندیس DataLabel مشخص شده در مجموعه را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

برچسب داده را برای نقطه داده‌ای که دارای اندیس مشخص است دریافت می‌کند.

--------------------

راه‌یک دیگر برای دسترسی به برچسب داده به این صورت است: - getSeries().getDataPoints().get_Item(i).getLabel() - مدیریت ویژگی‌های برچسب.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

قالب پیش‌فرض تمام برچسب‌های داده در مجموعه را برمی‌گرداند. فقط-خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازمی‌گرداند:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

قالب خطوط راهنمای برچسب‌های داده را نمایان می‌کند. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False به این معناست که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر false هستند). فقط-خواندنی  boolean .

--------------------

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده باشد می‌توانید آن را با متد Hide() به‌صورت پیش‌فرض مخفی کنید. ولی اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید برچسب داده را «به‌صورت پیش‌فرض قابل مشاهده» کنید با تنظیم پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true.

**بازمی‌گرداند:**
boolean

### hide() {#hide--}
```
public abstract void hide()
```

برچسب داده را به‌صورت پیش‌فرض مخفی کنید با تنظیم تمام پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. پس از این IsVisible برابر false خواهد بود.

--------------------

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false) می‌توانید برچسب داده را «به‌صورت پیش‌فرض قابل مشاهده» کنید با تنظیم پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. فقط-خواندنی  int .

**بازمی‌گرداند:**
int

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد کل برچسب‌های داده در مجموعه را دریافت می‌کند. فقط-خواندنی  int .

**بازمی‌گرداند:**
int

### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

سری نمودار والد را برمی‌گرداند. فقط-خواندنی [IChartSeries](../../com.aspose.slides/ichartseries).

**بازمی‌گرداند:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

اندیس DataLabel مشخص شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel برای جستجو. |

**بازمی‌گرداند:**
int - اندیس یک DataLabel یا -1 اگر DataLabel جزء این مجموعه نباشد.