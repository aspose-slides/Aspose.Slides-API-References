---
title: IChartPlotArea
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: خواص عنوان نمودار را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ichartplotarea/
---
**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

خواص عنوان نمودار را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFormat()](#getFormat--) | قالب ناحیهٔ نمودار را برمی‌گرداند. |
| [getLayoutTargetType()](#getLayoutTargetType--) | اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که آیا ناحیهٔ نمودار را بر اساس داخل آن (بدون شامل شدن محور و برچسب‌های محور) یا بیرون (شامل محور و برچسب‌های محور) چیدمان کنیم. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که آیا ناحیهٔ نمودار را بر اساس داخل آن (بدون شامل شدن محور و برچسب‌های محور) یا بیرون (شامل محور و برچسب‌های محور) چیدمان کنیم. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


قالب ناحیهٔ نمودار را برمی‌گرداند. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

**باز می‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که آیا ناحیهٔ نمودار را بر اساس داخل آن (بدون شامل شدن محور و برچسب‌های محور) یا بیرون (شامل محور و برچسب‌های محور) چیدمان کنیم. قابل-نوشتن [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**باز می‌گرداند:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که آیا ناحیهٔ نمودار را بر اساس داخل آن (بدون شامل شدن محور و برچسب‌های محور) یا بیرون (شامل محور و برچسب‌های محور) چیدمان کنیم. قابل-نوشتن [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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