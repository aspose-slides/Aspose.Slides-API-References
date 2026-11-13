---
title: DataLabel
second_title: Referencia de API de Aspose.Slides para Java
description: Representa etiquetas de serie.
type: docs
url: /es/com.aspose.slides/datalabel/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Representa etiquetas de serie.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Crea una nueva instancia de la clase DataLabel. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Devuelve la gráfica principal. |
| [isVisible()](#isVisible--) | Falso significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*- (ShowValue, ...) son falsas). |
| [hide()](#hide--) | Oculta la etiqueta de datos estableciendo todas las banderas Show*- (ShowValue, ...) en estado false. |
| [getActualLabelText()](#getActualLabelText--) | Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o en el valor TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding con el texto del parámetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Puede contener un texto con formato enriquecido. |
| [getTextFormat()](#getTextFormat--) | Devuelve el formato de texto. |
| [getX()](#getX--) | Devuelve o establece la coordenada x de un título como una fracción del ancho de la gráfica. |
| [setX(float value)](#setX-float-) | Devuelve o establece la coordenada x de un título como una fracción del ancho de la gráfica. |
| [getY()](#getY--) | Devuelve o establece la coordenada y de un título como una fracción de la altura de la gráfica. |
| [setY(float value)](#setY-float-) | Devuelve o establece la coordenada y de un título como una fracción de la altura de la gráfica. |
| [getWidth()](#getWidth--) | Devuelve o establece el ancho de un título como una fracción del ancho de la gráfica. |
| [setWidth(float value)](#setWidth-float-) | Devuelve o establece el ancho de un título como una fracción del ancho de la gráfica. |
| [getHeight()](#getHeight--) | Devuelve o establece la altura de un título como una fracción de la altura de la gráfica. |
| [setHeight(float value)](#setHeight-float-) | Devuelve o establece la altura de un título como una fracción de la altura de la gráfica. |
| [getRight()](#getRight--) | Derecha. |
| [getBottom()](#getBottom--) | Inferior. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Devuelve el formato de la etiqueta de datos. |
| [getValueFromCell()](#getValueFromCell--) | Obtiene o establece la celda de datos del libro de trabajo. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtiene o establece la celda de datos del libro de trabajo. |
| [getLabelShapeType()](#getLabelShapeType--) | Obtiene o establece el tipo de forma de la etiqueta de datos. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Obtiene o establece el tipo de forma de la etiqueta de datos. |
| [getActualX()](#getActualX--) | Especifica la ubicación real x (izquierda) del elemento de la gráfica respecto a la esquina superior izquierda de la gráfica. |
| [getActualY()](#getActualY--) | Especifica la parte superior real del elemento de la gráfica respecto a la esquina superior izquierda de la gráfica. |
| [getActualWidth()](#getActualWidth--) | Especifica el ancho real del elemento de la gráfica. |
| [getActualHeight()](#getActualHeight--) | Especifica la altura real del elemento de la gráfica. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Crea una nueva instancia de la clase DataLabel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint padre. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve la gráfica principal. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Falso significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*- (ShowValue, ...) son falsas). Solo lectura  boolean .

--------------------

Si la etiqueta de datos es visible puede ocultarla con el método Hide(). Pero si la etiqueta de datos no es visible (IsVisible es false) puede hacerla visible estableciendo las banderas Show*- (ShowValue, ...) en estado true.

**Devuelve:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Oculta la etiqueta de datos estableciendo todas las banderas Show*- (ShowValue, ...) en estado false. IsVisible será false después de esto.

--------------------

Si la etiqueta de datos no es visible (IsVisible es false) puede hacerla visible estableciendo las banderas Show*- (ShowValue, ...) en estado true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o en el valor TextFrameForOverriding.Text.

**Devuelve:**
java.lang.String - El objeto java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializa TextFrameForOverriding con el texto del parámetro "text". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto para un nuevo TextFrameForOverriding. |

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, entonces este valor de texto con formato sobrescribe el texto autogenerado de la etiqueta de datos. El texto autogenerado de la etiqueta de datos significa el texto gestionado por las propiedades ShowSeriesName, ShowValue, ... y formateado con la propiedad TextFormatManager.TextFormat. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Devuelve el formato de texto. Solo lectura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Devuelve:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Devuelve o establece la coordenada x de un título como una fracción del ancho de la gráfica. Lectura/escritura  float .

**Devuelve:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Devuelve o establece la coordenada x de un título como una fracción del ancho de la gráfica. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Devuelve o establece la coordenada y de un título como una fracción de la altura de la gráfica. Lectura/escritura  float .

**Devuelve:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Devuelve o establece la coordenada y de un título como una fracción de la altura de la gráfica. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Devuelve o establece el ancho de un título como una fracción del ancho de la gráfica. Lectura/escritura  float .

**Devuelve:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Devuelve o establece el ancho de un título como una fracción del ancho de la gráfica. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Devuelve o establece la altura de un título como una fracción de la altura de la gráfica. Lectura/escritura  float .

**Devuelve:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Devuelve o establece la altura de un título como una fracción de la altura de la gráfica. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Derecha. Solo lectura  float .

**Devuelve:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Inferior. Solo lectura  float .

**Devuelve:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Devuelve el formato de la etiqueta de datos. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Obtiene o establece la celda de datos del libro de trabajo. Aplicado si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true.

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Obtiene o establece la celda de datos del libro de trabajo. Aplicado si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Obtiene o establece el tipo de forma de la etiqueta de datos. Devuelve [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si no se define una forma.

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
public final void setLabelShapeType(int value)
```

Obtiene o establece el tipo de forma de la etiqueta de datos. Devuelve [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si no se define una forma.

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
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Especifica la ubicación real x (izquierda) del elemento de la gráfica respecto a la esquina superior izquierda de la gráfica. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Especifica la parte superior real del elemento de la gráfica respecto a la esquina superior izquierda de la gráfica. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Especifica el ancho real del elemento de la gráfica. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Especifica la altura real del elemento de la gráfica. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva principal de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)