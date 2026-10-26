---
title: IChartPlotArea
second_title: Aspose.Slides pro Android prostřednictvím referenčního dokumentu Java API
description: Reprezentuje vlastnosti názvu grafu.
type: docs
url: /cs/com.aspose.slides/ichartplotarea/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Reprezentuje vlastnosti názvu grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFormat()](#getFormat--) | Vrací formát oblasti vykreslování. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Pokud je rozložení oblasti vykreslování definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast vykreslování podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Pokud je rozložení oblasti vykreslování definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast vykreslování podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vrací formát oblasti vykreslování. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Pokud je rozložení oblasti vykreslování definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast vykreslování podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). Čtení/Zápis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

Pokud je rozložení oblasti vykreslování definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast vykreslování podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). Čtení/Zápis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
