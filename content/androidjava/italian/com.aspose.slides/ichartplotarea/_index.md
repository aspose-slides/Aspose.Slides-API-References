---
title: IChartPlotArea
second_title: Aspose.Slides per Android tramite API Java di riferimento
description: Rappresenta le proprietà del titolo del grafico.
type: docs
url: /it/com.aspose.slides/ichartplotarea/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Rappresenta le proprietà del titolo del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) | Restituisce il formato di un'area del grafico. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico al suo interno (escludendo assi e etichette degli assi) o all'esterno (includendo assi e etichette degli assi). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico al suo interno (escludendo assi e etichette degli assi) o all'esterno (includendo assi e etichette degli assi). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Restituisce il formato di un'area del grafico. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico al suo interno (escludendo assi e etichette degli assi) o all'esterno (includendo assi e etichette degli assi). Lettura/scrittura [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Restituisce:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico al suo interno (escludendo assi e etichette degli assi) o all'esterno (includendo assi e etichette degli assi). Lettura/scrittura [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |