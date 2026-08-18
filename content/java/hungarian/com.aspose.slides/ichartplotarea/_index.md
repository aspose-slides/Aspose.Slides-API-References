---
title: IChartPlotArea
second_title: Aspose.Slides for Java API Referenciája
description: A diagramcím tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ichartplotarea/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

A diagramcím tulajdonságait reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFormat()](#getFormat--) | Visszaadja a diagramterület formátumát. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Ha a diagramterület elrendezése kézzel van meghatározva, ez a tulajdonság meghatározza, hogy a diagramterületet annak belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján kell elrendezni. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Ha a diagramterület elrendezése kézzel van meghatározva, ez a tulajdonság meghatározza, hogy a diagramterületet annak belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján kell elrendezni. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a diagramterület formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Ha a diagramterület elrendezése kézzel van meghatározva, ez a tulajdonság meghatározza, hogy a diagramterületet annak belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján kell elrendezni. Olvasás/írás [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Visszatér:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Ha a diagramterület elrendezése kézzel van meghatározva, ez a tulajdonság meghatározza, hogy a diagramterületet annak belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján kell elrendezni. Olvasás/írás [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |