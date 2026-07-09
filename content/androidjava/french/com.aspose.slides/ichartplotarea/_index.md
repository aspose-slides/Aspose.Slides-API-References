---
title: IChartPlotArea
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les propriétés du titre du graphique.
type: docs
url: /fr/com.aspose.slides/ichartplotarea/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Représente les propriétés du titre du graphique.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Renvoie le format d'une zone de tracé. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Si la disposition de la zone de tracé est définie manuellement, cette propriété indique si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés d'axe) ou par son extérieur (en incluant les axes et les libellés d'axe). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Si la disposition de la zone de tracé est définie manuellement, cette propriété indique si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés d'axe) ou par son extérieur (en incluant les axes et les libellés d'axe). |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Renvoie le format d'une zone de tracé. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)

### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Si la disposition de la zone de tracé est définie manuellement, cette propriété indique si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés d'axe) ou par son extérieur (en incluant les axes et les libellés d'axe). Lecture/écriture [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
**Returns:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |