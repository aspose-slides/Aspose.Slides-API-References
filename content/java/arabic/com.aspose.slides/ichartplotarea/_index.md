---
title: IChartPlotArea
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل خصائص عنوان المخطط.
type: docs
url: /ar/com.aspose.slides/ichartplotarea/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

يمثل خصائص عنوان المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) | يرد تنسيق منطقة الرسم. |
| [getLayoutTargetType()](#getLayoutTargetType--) | إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط المنطقة من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المح轴). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط المنطقة من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المح轴). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يرجع تنسيق منطقة الرسم. للقراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط المنطقة من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المح轴). قراءة/كتابة [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**الإرجاع:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط المنطقة من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المح轴). قراءة/كتابة [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |