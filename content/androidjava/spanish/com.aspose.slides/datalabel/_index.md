---
title: DataLabel
second_title: Aspose.Slides para Android mediante la referencia de API Java
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

Representa etiquetas de series.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Crea una nueva instancia de la clase DataLabel. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Devuelve el gráfico padre. |
| [isVisible()](#isVisible--) | False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son false). |
| [hide()](#hide--) | Oculta la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) en estado false. |
| [getActualLabelText()](#getActualLabelText--) | Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o el valor TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding con el texto del parámetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Puede contener un texto con formato enriquecido. |
| [getTextFormat()](#getTextFormat--) | Devuelve el formato de texto. |
| [getX()](#getX--) | Devuelve o establece la coordenada x de un título como una fracción del ancho del gráfico. |
| [setX(float value)](#setX-float-) | Devuelve o establece la coordenada x de un título como una fracción del ancho del gráfico. |
| [getY()](#getY--) | Devuelve o establece la coordenada y de un título como una fracción de la altura del gráfico. |
| [setY(float value)](#setY-float-) | Devuelve o establece la coordenada y de un título como una fracción de la altura del gráfico. |
| [getWidth()](#getWidth--) | Devuelve o establece el ancho de un título como una fracción del ancho del gráfico. |
| [setWidth(float value)](#setWidth-float-) | Devuelve o establece el ancho de un título como una fracción del ancho del gráfico. |
| [getHeight()](#getHeight--) | Devuelve o establece la altura de un título como una fracción de la altura del gráfico. |
| [setHeight(float value)](#setHeight-float-) | Devuelve o establece la altura de un título como una fracción de la altura del gráfico. |
| [getRight()](#getRight--) | Derecha. |
| [getBottom()](#getBottom--) | Inferior. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Devuelve el formato de etiqueta de datos. |
| [getValueFromCell()](#getValueFromCell--) | Obtiene o establece la celda de datos del libro de trabajo. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtiene o establece la celda de datos del libro de trabajo. |
| [getActualX()](#getActualX--) | Especifica la ubicación real x (izquierda) del elemento del gráfico relativo a la esquina superior izquierda del gráfico. |
| [getActualY()](#getActualY--) | Especifica la parte superior real del elemento del gráfico relativo a la esquina superior izquierda del gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica el ancho real del elemento del gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica la altura real del elemento del gráfico. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre de un FillFormat. |
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

Devuelve el gráfico padre. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son false). Solo lectura  boolean .

**Devuelve:**
boolean

If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state.

**Devuelve:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Oculta la etiqueta de datos configurando todas las banderas Show*-flags (ShowValue, ...) al estado false. IsVisible será false después de esto.

If data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o el valor TextFrameForOverriding.Text.

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

Puede contener un texto con formato enriquecido. Si esta propiedad no es null, entonces este valor de texto formateado sobrescribe el texto autogenerado de la etiqueta de datos. El texto autogenerado de la etiqueta de datos significa el texto gestionado por las propiedades ShowSeriesName, ShowValue, ... y está formateado con la propiedad TextFormatManager.TextFormat. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

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

Devuelve o establece la coordenada x de un título como una fracción del ancho del gráfico. Lectura/escritura  float .

**Devuelve:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Establece la coordenada x de un título como una fracción del ancho del gráfico. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Devuelve o establece la coordenada y de un título como una fracción de la altura del gráfico. Lectura/escritura  float .

**Devuelve:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Establece la coordenada y de un título como una fracción de la altura del gráfico. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Devuelve o establece el ancho de un título como una fracción del ancho del gráfico. Lectura/escritura  float .

**Devuelve:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Establece el ancho de un título como una fracción del ancho del gráfico. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Devuelve o establece la altura de un título como una fracción de la altura del gráfico. Lectura/escritura  float .

**Devuelve:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Establece la altura de un título como una fracción de la altura del gráfico. Lectura/escritura  float .

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

Devuelve el formato de etiqueta de datos. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

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
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Especifica la ubicación real x (izquierda) del elemento del gráfico relativo a la esquina superior izquierda del gráfico. Llamar al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float .

**Devuelve:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Especifica la parte superior real del elemento del gráfico relative a la esquina superior izquierda del gráfico. Llamar al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float .

**Devuelve:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Especifica el ancho real del elemento del gráfico. Llamar al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float .

**Devuelve:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Especifica la altura real del elemento del gráfico. Llamar al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float .

**Devuelve:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación padre de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)