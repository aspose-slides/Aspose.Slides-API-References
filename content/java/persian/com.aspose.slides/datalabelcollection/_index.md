---
title: DataLabelCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش برچسب‌های سری.
type: docs
url: /fa/com.aspose.slides/datalabelcollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

نمایش برچسب‌های سری.

## متدها

| متد | توضیح |
| --- | --- |
| [getChart()](#getChart--) | چارت والد را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [isVisible()](#isVisible--) | مقدار False به این معنی است که برچسب داده به طور پیش‌فرض قابل مشاهده نیست (و بنابراین تمام Show\*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر false هستند). |
| [hide()](#hide--) | برچسب داده را به طور پیش‌فرض مخفی کنید با تنظیم تمام Show\*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | قالب پیش‌فرض برچسب داده را دریافت می‌کند. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | قالب خطوط ره‌بر برچسب‌های داده را نمایش می‌دهد. |
| [getParentSeries()](#getParentSeries--) | سری والد را دریافت می‌کند. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | یک ایندکس از DataLabel مشخص‌شده در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | برچسب داده برای نقطه داده با ایندکس مشخص‌شده را دریافت می‌کند. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک FillFormat را برمی‌گرداند. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

چارت والد را برمی‌گرداند. فقط خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

یک شمارشگر که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

مقدار False به این معنی است که برچسب داده به طور پیش‌فرض قابل مشاهده نیست (و بنابراین تمام Show\*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر false هستند). فقط خواندنی boolean.

--------------------

اگر برچسب داده به طور پیش‌فرض قابل مشاهده باشد می‌توانید با متد Hide() آن را به طور پیش‌فرض مخفی کنید. اما اگر برچسب داده به طور پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید با تنظیم Show\*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true، برچسب داده را «به طور پیش‌فرض قابل مشاهده» کنید.

**بازگشت:**  
boolean

### hide() {#hide--}
```
public final void hide()
```

برچسب داده را به طور پیش‌فرض مخفی کنید با تنظیم تمام Show\*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. پس از این IsVisible برابر false خواهد بود.

--------------------

اگر برچسب داده به طور پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false است) می‌توانید با تنظیم Show\*-flags (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true، برچسب داده را «به طور پیش‌فرض قابل مشاهده» کنید.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**  
int

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**  
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

قالب پیش‌فرض برچسب داده را دریافت می‌کند. فقط خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازگشت:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

قالب خطوط ره‌بر برچسب‌های داده را نمایش می‌دهد. فقط خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**بازگشت:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

سری والد را دریافت می‌کند. فقط خواندنی [IChartSeries](../../com.aspose.slides/ichartseries).

**بازگشت:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

یک ایندکس از DataLabel مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel برای پیدا کردن. |

**بازگشت:**  
int - Index of a DataLabel or -1 if DataLabel not from this collection.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

برچسب داده برای نقطه داده با ایندکس مشخص‌شده را دریافت می‌کند.

روش جایگزین برای دسترسی به برچسب داده به این صورت است:
- series.getDataPoints().get_Item(i).getLabel()
- مدیریت ویژگی‌های برچسب.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. اگر هیچ شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) را برمی‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // نوع شکل تمام برچسب‌های داده در اولین سری را به Ellipse تنظیم کنید.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

تنظیم این ویژگی همچنین ویژگی IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) را برای تمام برچسب‌های داده در مجموعه به همان مقدار تنظیم می‌کند.

**بازگشت:**  
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. اگر هیچ شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) را برمی‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // نوع شکل تمام برچسب‌های داده در اولین سری را به Ellipse تنظیم کنید.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

تنظیم این ویژگی همچنین ویژگی IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) را برای تمام برچسب‌های داده در مجموعه به همان مقدار تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک FillFormat را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**  
[IPresentation](../../com.aspose.slides/ipresentation)