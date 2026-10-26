---
title: IDataLabelCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر برچسب‌های یک سری است.
type: docs
url: /fa/com.aspose.slides/idatalabelcollection/
---
**همه‌ٔ رابط‌های پیاده‌سازی شده:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

برچسب‌های یک سری را نشان می‌دهد.

## روش‌ها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برچسب داده را برای نقطه داده با شاخص مشخص شده دریافت می‌کند. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | قالب پیش‌فرض تمام برچسب‌های داده در مجموعه را بازمی‌گرداند. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | قالب خطوط راهنمای برچسب‌های داده را نشان می‌دهد. |
| [isVisible()](#isVisible--) | False به این معنی است که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat برابر false هستند). |
| [hide()](#hide--) | برچسب داده را به‌صورت پیش‌فرض مخفی کنید با تنظیم تمام پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat به حالت false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد کلی برچسب‌های داده در مجموعه را دریافت می‌کند. |
| [getParentSeries()](#getParentSeries--) | سری نمودار والد را بازمی‌گرداند. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | شاخص برچسب دادهٔ مشخص شده در مجموعه را بازمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

برچسب داده را برای نقطه داده با شاخص مشخص شده دریافت می‌کند.

--------------------

یک روش جایگزین برای دسترسی به برچسب داده این است: - getSeries().getDataPoints().get_Item(i).getLabel() - مدیریت ویژگی‌های برچسب.

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

قالب پیش‌فرض تمام برچسب‌های داده در مجموعه را بازمی‌گرداند. فقط-خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازمی‌گرداند:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

قالب خطوط راهنمای برچسب‌های داده را نشان می‌دهد. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
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

False به این معنی است که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat برابر false هستند). فقط-خواندنی  boolean .

--------------------

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده باشد، می‌توانید آن را به‌صورت پیش‌فرض مخفی کنید با متد Hide(). اما اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید برچسب داده را «قابل مشاهده به‌صورت پیش‌فرض» کنید با تنظیم پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat به حالت true.

**بازمی‌گرداند:**
boolean

### hide() {#hide--}
```
public abstract void hide()
```

برچسب داده را به‌صورت پیش‌فرض مخفی کنید با تنظیم تمام پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat به حالت false. پس از این IsVisible برابر false خواهد شد.

--------------------

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید برچسب داده را «قابل مشاهده به‌صورت پیش‌فرض» کنید با تنظیم پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat به حالت true.

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

تعداد کلی برچسب‌های داده در مجموعه را دریافت می‌کند. فقط-خواندنی  int .

**بازمی‌گرداند:**
int

### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

سری نمودار والد را بازمی‌گرداند. فقط-خواندنی [IChartSeries](../../com.aspose.slides/ichartseries).

**بازمی‌گرداند:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

شاخص برچسب دادهٔ مشخص شده در مجموعه را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | برچسب داده برای جستجو. |

**بازمی‌گرداند:**
int - شاخص یک DataLabel یا -1 اگر DataLabel از این مجموعه نباشد.