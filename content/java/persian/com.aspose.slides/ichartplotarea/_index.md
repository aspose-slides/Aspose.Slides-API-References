---
title: IChartPlotArea
second_title: مرجع API Aspose.Slides برای جاوا
description: خواص عنوان نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichartplotarea/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

خواص عنوان نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getFormat()](#getFormat--) | قالب یک ناحیه رسم را برمی‌گرداند. |
| [getLayoutTargetType()](#getLayoutTargetType--) | اگر چیدمان ناحیه رسم به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه رسم بر اساس داخل (بدون محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چیدمان شود. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | اگر چیدمان ناحیه رسم به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه رسم بر اساس داخل (بدون محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چیدمان شود. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

قالب یک ناحیه رسم را برمی‌گرداند. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

اگر چیدمان ناحیه رسم به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه رسم بر اساس داخل (بدون محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چیدمان شود. خواندنی/نوشتنی [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**بازگشت:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

اگر چیدمان ناحیه رسم به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه رسم بر اساس داخل (بدون محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چیدمان شود. خواندنی/نوشتنی [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |