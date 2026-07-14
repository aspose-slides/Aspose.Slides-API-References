---
title: DataLabelCollection
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: برچسب‌های یک سری را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/datalabelcollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

برچسب‌های یک سری را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getChart()](#getChart--) | نمودار والد را بازمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده را بازمی‌گرداند که از مجموعه عبور می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک تکرارگر جاوا برای کل مجموعه را بازمی‌گرداند. |
| [isVisible()](#isVisible--) | False به این معنی است که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show\*- (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر False هستند). |
| [hide()](#hide--) | برچسب داده را به‌صورت پیش‌فرض مخفی می‌کند با تنظیم همه پرچم‌های Show\*- (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت False. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | قالب پیش‌فرض برچسب داده را دریافت می‌کند. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | قالب خطوط راهنمای برچسب‌های داده را نشان می‌دهد. |
| [getParentSeries()](#getParentSeries--) | سری والد را دریافت می‌کند. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | یک اندیس از DataLabel مشخص شده در مجموعه را بازمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | برچسب داده برای نقطه داده با اندیس مشخص شده را دریافت می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را بازمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه‌ی والد یک FillFormat را بازمی‌گرداند. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را بازمی‌گرداند. فقط خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

یک شمارنده را بازمی‌گرداند که از مجموعه عبور می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

یک تکرارگر جاوا برای کل مجموعه را بازمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - یک java.util.Iterator برای کل مجموعه.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False به این معنی است که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show\*- (ShowValue, ...) ویژگی DefaultDataLabelFormat برابر False هستند). فقط خواندنی بولی.

---

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده باشد می‌توانید با متد Hide() آن را به‌صورت پیش‌فرض مخفی کنید. اما اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false) می‌توانید با تنظیم پرچم‌های Show\*- (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true، برچسب داده را «قابل مشاهده به‌صورت پیش‌فرض» کنید.

**بازگشت:**
boolean

### hide() {#hide--}
```
public final void hide()
```

برچسب داده را به‌صورت پیش‌فرض مخفی می‌کند با تنظیم همه پرچم‌های Show\*- (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت false. پس از این IsVisible برابر false خواهد بود.

---

اگر برچسب داده به‌صورت پیش‌فرض قابل مشاهده نباشد (IsVisible برابر false) می‌توانید با تنظیم پرچم‌های Show\*- (ShowValue, ...) ویژگی DefaultDataLabelFormat به حالت true، برچسب داده را «قابل مشاهده به‌صورت پیش‌فرض» کنید.

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

قالب خطوط راهنمای برچسب‌های داده را نشان می‌دهد. فقط خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

---

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

یک اندیس از DataLabel مشخص شده در مجموعه را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel برای یافتن. |

**بازگشت:**
int - اندیس یک DataLabel یا -1 اگر DataLabel متعلق به این مجموعه نباشد.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

برچسب داده برای نقطه داده با اندیس مشخص شده را دریافت می‌کند.

---

راه‌حل جایگزین برای دسترسی به برچسب داده این است: - series.getDataPoints().get_Item(i).getLabel() - مدیریت ویژگی‌های برچسب.

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

اسلاید والد یک FillFormat را بازمی‌گرداند. فقط خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه‌ی والد یک FillFormat را بازمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)