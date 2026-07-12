---
title: IChartPlotArea
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Eigenschaften des Diagrammtitels dar.
type: docs
url: /de/com.aspose.slides/ichartplotarea/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Stellt Eigenschaften des Diagrammtitels dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) | Gibt das Format eines Plotbereichs zurück. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Wenn das Layout des Plotbereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plotbereich innerhalb (ohne Achsen und Achsenbeschriftungen) oder außerhalb (mit Achsen und Achsenbeschriftungen) angeordnet wird. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Wenn das Layout des Plotbereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plotbereich innerhalb (ohne Achsen und Achsenbeschriftungen) oder außerhalb (mit Achsen und Achsenbeschriftungen) angeordnet wird. |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Gibt das Format eines Plotbereichs zurück. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Wenn das Layout des Plotbereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plotbereich innerhalb (ohne Achsen und Achsenbeschriftungen) oder außerhalb (mit Achsen und Achsenbeschriftungen) angeordnet wird. Lesen/Schreiben [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Rückgabe:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Wenn das Layout des Plotbereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plotbereich innerhalb (ohne Achsen und Achsenbeschriftungen) oder außerhalb (mit Achsen und Achsenbeschriftungen) angeordnet wird. Lesen/Schreiben [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |