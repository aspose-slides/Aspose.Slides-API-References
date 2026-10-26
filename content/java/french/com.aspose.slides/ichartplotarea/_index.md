---
title: IChartPlotArea
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés du titre du graphique.
type: docs
url: /fr/com.aspose.slides/ichartplotarea/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Représente les propriétés du titre du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Renvoie le format d’une zone de tracé. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Si la disposition de la zone de tracé est définie manuellement, cette propriété précise si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés des axes) ou par son extérieur (en incluant les axes et les libellés des axes). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Si la disposition de la zone de tracé est définie manuellement, cette propriété précise si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés des axes) ou par son extérieur (en incluant les axes et les libellés des axes). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Renvoie le format d’une zone de tracé. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Retourne:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Si la disposition de la zone de tracé est définie manuellement, cette propriété précise si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés des axes) ou par son extérieur (en incluant les axes et les libellés des axes). Lecture/écriture [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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


**Retourne:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Si la disposition de la zone de tracé est définie manuellement, cette propriété précise si la zone de tracé doit être disposée par son intérieur (sans inclure les axes et les libellés des axes) ou par son extérieur (en incluant les axes et les libellés des axes). Lecture/écriture [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |