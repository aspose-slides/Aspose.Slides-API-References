---
title: IChartPlotArea
second_title: Aspose.Slides for Android – Java API Referansı
description: Grafik başlığı özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartplotarea/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Grafik başlığı özelliklerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) | Bir grafik alanının biçimini döndürür. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Grafik alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (ekseni ve eksen etiketlerini içermeyen) veya dış kısmına (ekseni ve eksen etiketlerini içeren) yerleştirip yerleştirmeyeceğini belirtir. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Grafik alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (ekseni ve eksen etiketlerini içermeyen) veya dış kısmına (ekseni ve eksen etiketlerini içeren) yerleştirip yerleştirmeyeceğini belirtir. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Bir grafik alanının biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Grafik alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (ekseni ve eksen etiketlerini içermeyen) veya dış kısmına (ekseni ve eksen etiketlerini içeren) yerleştirip yerleştirmeyeceğini belirtir. Okunabilir/Yazılabilir [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))

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


**Döndürür:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Grafik alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik grafik alanını iç kısmına (ekseni ve eksen etiketlerini içermeyen) veya dış kısmına (ekseni ve eksen etiketlerini içeren) yerleştirip yerleştirmeyeceğini belirtir. Okunabilir/Yazılabilir [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int))

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