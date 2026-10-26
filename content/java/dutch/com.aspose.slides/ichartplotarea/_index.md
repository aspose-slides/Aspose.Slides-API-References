---
title: IChartPlotArea
second_title: Aspose.Slides voor Java API Referentie
description: Stelt de eigenschappen van de grafiektitel voor.
type: docs
url: /nl/com.aspose.slides/ichartplotarea/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Stelt de eigenschappen van de grafiektitel voor.
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) | Retourneert het formaat van een plotgebied. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden ingedeeld op basis van de binnenkant (niet inclusief axis en axis labels) of buitenkant (inclusief axis en axis labels). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden ingedeeld op basis van de binnenkant (niet inclusief axis en axis labels) of buitenkant (inclusief axis en axis labels). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Retourneert het formaat van een plotgebied. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden ingedeeld op basis van de binnenkant (niet inclusief axis en axis labels) of buitenkant (inclusief axis en axis labels). Lezen/schrijven [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Retour:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden ingedeeld op basis van de binnenkant (niet inclusief axis en axis labels) of buitenkant (inclusief axis en axis labels). Lezen/schrijven [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |