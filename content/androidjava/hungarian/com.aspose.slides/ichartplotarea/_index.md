---
title: IChartPlotArea
second_title: Aspose.Slides Androidra vonatkozó Java API hivatkozás
description: A diagramcím tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ichartplotarea/
---
**Az összes implementált interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

A diagramcím tulajdonságait képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFormat()](#getFormat--) | Visszaadja a diagramterület formátumát. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Ha a diagramterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a diagramterületet a belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy a külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján helyezzük el. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Ha a diagramterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a diagramterületet a belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy a külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján helyezzük el. |
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

Ha a diagramterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a diagramterületet a belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy a külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján helyezzük el. Olvasás/írás [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

Ha a diagramterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a diagramterületet a belseje (a tengelyeket és tengelycímkéket nem tartalmazva) vagy a külseje (a tengelyeket és tengelycímkéket tartalmazva) alapján helyezzük el. Olvasás/írás [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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