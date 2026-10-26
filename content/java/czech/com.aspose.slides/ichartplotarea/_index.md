---
title: IChartPlotArea
second_title: Aspose.Slides pro Java API Reference
description: Představuje vlastnosti titulku grafu.
type: docs
url: /cs/com.aspose.slides/ichartplotarea/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Představuje vlastnosti titulku grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFormat()](#getFormat--) | Vrací formát vykreslovací oblasti. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Pokud je rozvržení vykreslovací oblasti definováno ručně, tato vlastnost určuje, zda rozvrhovat oblast podle jejího vnitřku (neobsahuje osy a popisky os) nebo podle vnějšího okraje (včetně os a popisek os). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Pokud je rozvržení vykreslovací oblasti definováno ručně, tato vlastnost určuje, zda rozvrhovat oblast podle jejího vnitřku (neobsahuje osy a popisky os) nebo podle vnějšího okraje (včetně os a popisek os). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vrací formát vykreslovací oblasti. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Pokud je rozvržení vykreslovací oblasti definováno ručně, tato vlastnost určuje, zda rozvrhovat oblast podle jejího vnitřku (neobsahuje osy a popisky os) nebo podle vnějšího okraje (včetně os a popisek os). Čtení/zápis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Vrací:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Pokud je rozvržení vykreslovací oblasti definováno ručně, tato vlastnost určuje, zda rozvrhovat oblast podle jejího vnitřku (neobsahuje osy a popisky os) nebo podle vnějšího okraje (včetně os a popisek os). Čtení/zápis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |