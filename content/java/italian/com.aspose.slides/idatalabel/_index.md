---
title: IDataLabel
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Rappresenta le etichette di una serie.
## Metodi

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). |
| [hide()](#hide--) | Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returns format of the data label. |
| [getValueFromCell()](#getValueFromCell--) | Gets or sets workbook data cell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Gets or sets workbook data cell. |
| [getActualLabelText()](#getActualLabelText--) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [getLabelShapeType()](#getLabelShapeType--) | Gets or sets the shape type of the data label. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Gets or sets the shape type of the data label. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). Booleano di sola lettura.

--------------------

If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show\*-flags (ShowValue, ...) to true state.

**Restituisce:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. IsVisible will be false after this.

--------------------

If data label is not visible (IsVisible is false) you can make data label visible with setting Show\*-flags (ShowValue, ...) to true state.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


Returns format of the data label. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value.

**Restituisce:**
java.lang.String - Actual label text String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```


Gets or sets the shape type of the data label. Returns [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) if no shape is defined.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Imposta il tipo di forma della prima etichetta dati a Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```


Gets or sets the shape type of the data label. Returns [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) if no shape is defined.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Imposta il tipo di forma della prima etichetta dati a Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |