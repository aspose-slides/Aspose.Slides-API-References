---
title: DataLabelCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر برچسب‌های سری است.
type: docs
url: /fa/com.aspose.slides/datalabelcollection/
---
**وراثت:**
java.lang.Object, com.aspose.slides.DomObject

**تمام واسط‌های پیاده‌سازی شده:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

نمایانگر برچسب‌های سری است.
## متدها

| متد | توضیح |
| --- | --- |
| [getChart()](#getChart--) | نمودار chart والد را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator را برمی‌گرداند که از طریق مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه را برمی‌گرداند. |
| [isVisible()](#isVisible--) | False به این معنی است که DataLabel به‌طور پیش‌فرض قابل مشاهده نیست (و بنابراین تمام Show*-flags (ShowValue, ...) از ویژگی DefaultDataLabelFormat برابر false هستند). |
| [hide()](#hide--) | DataLabel را به‌طور پیش‌فرض مخفی می‌کند با تنظیم تمام Show*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به وضعیت false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | تعداد DataLabelهای قابل مشاهده در مجموعه را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد تمام DataLabelها در مجموعه را دریافت می‌کند. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | قالب پیش‌فرض DataLabel را دریافت می‌کند. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | قالب خطوط رهبری DataLabelها را نمایان می‌کند. |
| [getParentSeries()](#getParentSeries--) | سری والد را دریافت می‌کند. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | شاخص DataLabel مشخص‌شده در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | DataLabel برای نقطه داده با شاخص مشخص را دریافت می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه presentation والد یک FillFormat را برمی‌گرداند. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار chart والد را برمی‌گرداند. فقط‌خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

یک enumerator را برمی‌گرداند که از طریق مجموعه تکرار می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

یک java iterator برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - یک java.util.Iterator برای کل مجموعه.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False به این معنی است که DataLabel به‌طور پیش‌فرض قابل مشاهده نیست (و بنابراین تمام Show*-flags (ShowValue, ...) از ویژگی DefaultDataLabelFormat برابر false هستند). فقط‌خواندنی boolean.

--------------------

اگر DataLabel به‌طور پیش‌فرض قابل مشاهده باشد می‌توانید آن را با متد Hide() به‌طور پیش‌فرض مخفی کنید. اما اگر DataLabel به‌طور پیش‌فرض قابل مشاهده نیست (IsVisible برابر false است) می‌توانید DataLabel را «به‌طور پیش‌فرض قابل مشاهده» کنید با تنظیم Show*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true.

**بازگشت:**
boolean
### hide() {#hide--}
```
public final void hide()
```

DataLabel را به‌طور پیش‌فرض مخفی می‌کند با تنظیم تمام Show*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به وضعیت false. پس از این IsVisible برابر false خواهد بود.

--------------------

اگر DataLabel به‌طور پیش‌فرض قابل مشاهده نیست (IsVisible برابر false است) می‌توانید DataLabel را «به‌طور پیش‌فرض قابل مشاهده» کنید با تنظیم Show*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

تعداد DataLabelهای قابل مشاهده در مجموعه را دریافت می‌کند. فقط‌خواندنی int.

**بازگشت:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد تمام DataLabelها در مجموعه را دریافت می‌کند. فقط‌خواندنی int.

**بازگشت:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

قالب پیش‌فرض DataLabel را دریافت می‌کند. فقط‌خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازگشت:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

قالب خطوط رهبری DataLabelها را نمایان می‌کند. فقط‌خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> مثال:
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


**بازگشت:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

سری والد را دریافت می‌کند. فقط‌خواندنی [IChartSeries](../../com.aspose.slides/ichartseries).

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

شاخص DataLabel مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel برای یافتن. |

**بازگشت:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

DataLabel برای نقطه داده با شاخص مشخص را دریافت می‌کند.

--------------------

روش جایگزین برای دسترسی به DataLabel این است: - series.getDataPoints().get_Item(i).getLabel() - مدیریت ویژگی‌های برچسب.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط‌خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه presentation والد یک FillFormat را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)