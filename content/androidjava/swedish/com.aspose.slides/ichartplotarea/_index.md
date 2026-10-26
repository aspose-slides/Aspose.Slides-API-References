---
title: IChartPlotArea
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för diagramtitel.
type: docs
url: /sv/com.aspose.slides/ichartplotarea/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Representerar egenskaper för diagramtitel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) | Returnerar formatet för ett plot area. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Om layouten för plot area definierats manuellt specificerar denna egenskap huruvida plot area ska layoutas efter dess insida (exklusive axis och axis labels) eller utsida (inklusive axis och axis labels). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Om layouten för plot area definierats manuellt specificerar denna egenskap huruvida plot area ska layoutas efter dess insida (exklusive axis och axis labels) eller utsida (inklusive axis och axis labels). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Returnerar formatet för ett plot area. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Om layouten för plot area definierats manuellt specificerar denna egenskap huruvida plot area ska layoutas efter dess insida (exklusive axis och axis labels) eller utsida (inklusive axis och axis labels). Läs/skriv [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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


**Returnerar:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Om layouten för plot area definierats manuellt specificerar denna egenskap huruvida plot area ska layoutas efter dess insida (exklusive axis och axis labels) eller utsida (inklusive axis och axis labels). Läs/skriv [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |