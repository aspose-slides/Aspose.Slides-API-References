---
title: IDataLabelCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر برچسب‌های سری.
type: docs
url: /fa/com.aspose.slides/idatalabelcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

نمایش برچسب‌های یک سری.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برچسب داده را برای نقطه داده با شاخص مشخص دریافت می‌کند. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | قالب پیش‌فرض تمام برچسب‌های داده در مجموعه را برمی‌گرداند. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | نمایش قالب خطوط رهبری برچسب‌های داده. |
| [isVisible()](#isVisible--) | مقدار False به این معنی است که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین همه پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر false هستند). |
| [hide()](#hide--) | برچسب داده را به‌صورت پیش‌فرض مخفی می‌کند با تنظیم همه پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند. |
| [getParentSeries()](#getParentSeries--) | سری نمودار والد را برمی‌گرداند. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | شاخص DataLabel مشخص شده در مجموعه را برمی‌گرداند. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

برچسب داده را برای نقطه داده با شاخص مشخص دریافت می‌کند.

--------------------

روش جایگزین برای دسترسی به برچسب داده به صورت زیر است: - getSeries().getDataPoints().get_Item(i).getLabel() - مدیریت ویژگی‌های برچسب.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

قالب پیش‌فرض تمام برچسب‌های داده در مجموعه را برمی‌گرداند. فقط-خواندنی [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**بازگشت:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

نمایش قالب خطوط رهبری برچسب‌های داده. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

مقدار False به این معناست که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین همه پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر false هستند). فقط-خواندنی  boolean .

--------------------

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده باشد می‌توانید آن را با متد Hide() به‌صورت پیش‌فرض مخفی کنید. اما اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (IsVisible برابر false) می‌توانید با تنظیم پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true، برچسب را "قابل مشاهده به‌صورت پیش‌فرض" کنید.

**بازگشت:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

برچسب داده را به‌صورت پیش‌فرض مخفی می‌کند با تنظیم همه پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. پس از این IsVisible برابر false خواهد بود.

--------------------

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (IsVisible برابر false) می‌توانید با تنظیم پرچم‌های Show* (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true، برچسب را "قابل مشاهده به‌صورت پیش‌فرض" کنید.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. فقط-خواندنی  int .

**بازگشت:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند. فقط-خواندنی  int .

**بازگشت:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

سری نمودار والد را برمی‌گرداند. فقط-خواندنی [IChartSeries](../../com.aspose.slides/ichartseries).

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

شاخص DataLabel مشخص شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel برای یافتن. |

**بازگشت:**
int - شاخص یک DataLabel یا -1 اگر DataLabel متعلق به این مجموعه نباشد.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. اگر شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) را برمی‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // نوع شکل تمام برچسب‌های داده در سری اول را به Ellipse تنظیم کنید.
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
public abstract void setDefaultLabelShapeType(int value)
```

نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند. اگر شکلی تعریف نشده باشد [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) را برمی‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // نوع شکل تمام برچسب‌های داده در سری اول را به Ellipse تنظیم کنید.
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