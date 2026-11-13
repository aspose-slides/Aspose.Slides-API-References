---
title: IDataLabel
second_title: Referencia de API de Aspose.Slides para Java
description: Representa etiquetas de serie.
type: docs
url: /es/com.aspose.slides/idatalabel/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Representa etiquetas de serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [isVisible()](#isVisible--) | False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son falsas). |
| [hide()](#hide--) | Oculta la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) al estado falso. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Devuelve el formato de la etiqueta de datos. |
| [getValueFromCell()](#getValueFromCell--) | Obtiene o establece la celda de datos del libro de trabajo. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtiene o establece la celda de datos del libro de trabajo. |
| [getActualLabelText()](#getActualLabelText--) | Devuelve el texto real de la etiqueta basado en la configuración DataLabelFormat o el valor TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Obtiene o establece el tipo de forma de la etiqueta de datos. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Obtiene o establece el tipo de forma de la etiqueta de datos. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son falsas). Booleano solo lectura.

--------------------

Si la etiqueta de datos es visible, puede ocultarla con el método Hide(). Pero si la etiqueta de datos no es visible (IsVisible es false) puede hacerla visible estableciendo las banderas Show*-flags (ShowValue, ...) al estado verdadero.

**Devuelve:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Oculta la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) al estado falso. IsVisible será false después de esto.

--------------------

Si la etiqueta de datos no es visible (IsVisible es false) puede hacerla visible estableciendo las banderas Show*-flags (ShowValue, ...) al estado verdadero.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Devuelve el formato de la etiqueta de datos. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtiene o establece la celda de datos del libro de trabajo. Aplicado si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true.

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtiene o establece la celda de datos del libro de trabajo. Aplicado si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Devuelve el texto real de la etiqueta basado en la configuración DataLabelFormat o el valor TextFrameForOverriding.Text.

**Devuelve:**
java.lang.String - Texto real de la etiqueta
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Obtiene o establece el tipo de forma de la etiqueta de datos. Devuelve [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si no se ha definido una forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Establece el tipo de forma de la primera etiqueta de datos a Elipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Obtiene o establece el tipo de forma de la etiqueta de datos. Devuelve [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si no se ha definido una forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Establece el tipo de forma de la primera etiqueta de datos a Elipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |