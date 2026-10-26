---
title: IChartPlotArea
second_title: Aspose.Slides for Java API Referansı
description: Grafik başlığı özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartplotarea/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Grafik başlığı özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) | Bir çizim alanının biçimini döndürür. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Eğer çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik çizim alanının iç kısmına (ekseni ve eksen etiketlerini içermeyen) mı yoksa dış kısmına (ekseni ve eksen etiketlerini içeren) mı yerleştirileceğini belirtir. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Eğer çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik çizim alanının iç kısmına (ekseni ve eksen etiketlerini içermeyen) mı yoksa dış kısmına (ekseni ve eksen etiketlerini içeren) mı yerleştirileceğini belirtir. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Bir çizim alanının biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Eğer çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik çizim alanının iç kısmına (ekseni ve eksen etiketlerini içermeyen) mı yoksa dış kısmına (ekseni ve eksen etiketlerini içeren) mı yerleştirileceğini belirtir. Okuma/yazma [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
> 
```

**Döndürür:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Eğer çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik çizim alanının iç kısmına (ekseni ve eksen etiketlerini içermeyen) mı yoksa dış kısmına (ekseni ve eksen etiketlerini içeren) mı yerleştirileceğini belirtir. Okuma/yazma [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |