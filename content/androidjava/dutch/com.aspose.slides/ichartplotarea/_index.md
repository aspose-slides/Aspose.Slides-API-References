---
title: IChartPlotArea
second_title: Aspose.Slides voor Android via Java API-referentie
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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) | Geeft het formaat van een plotgebied terug. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Als de lay-out van het plotgebied handmatig is gedefinieerd, bepaalt deze eigenschap of het plotgebied wordt ingericht op basis van de binnenkant (exclusief assen en aslabels) of de buitenkant (inclusief assen en aslabels). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Als de lay-out van het plotgebied handmatig is gedefinieerd, bepaalt deze eigenschap of het plotgebied wordt ingericht op basis van de binnenkant (exclusief assen en aslabels) of de buitenkant (inclusief assen en aslabels). |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Geeft het formaat van een plotgebied terug. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)

### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Als de lay-out van het plotgebied handmatig is gedefinieerd, bepaalt deze eigenschap of het plotgebied wordt ingericht op basis van de binnenkant (exclusief assen en aslabels) of de buitenkant (inclusief assen en aslabels). Lezen/Schrijven [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

Als de lay-out van het plotgebied handmatig is gedefinieerd, bepaalt deze eigenschap of het plotgebied wordt ingericht op basis van de binnenkant (exclusief assen en aslabels) of de buitenkant (inclusief assen en aslabels). Lezen/Schrijven [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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