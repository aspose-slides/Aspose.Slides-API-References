---
title: Trendline
second_title: Aspose.Slides para Android a través de la referencia API de Java
description: Clase que representa la línea de tendencia de una serie de gráfico
type: docs
url: /es/com.aspose.slides/trendline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Clase que representa la línea de tendencia de una serie de gráfico
## Métodos

| Method | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Obtiene o establece el nombre de la línea de tendencia. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Obtiene o establece el nombre de la línea de tendencia. |
| [getTrendlineType()](#getTrendlineType--) | Obtiene o establece el tipo de línea de tendencia. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Obtiene o establece el tipo de línea de tendencia. |
| [getFormat()](#getFormat--) | Representa el formato de la línea de tendencia. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa el formato de la línea de tendencia. |
| [getBackward()](#getBackward--) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos para la serie que se está tendiendo. |
| [setBackward(double value)](#setBackward-double-) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos para la serie que se está tendiendo. |
| [getForward()](#getForward--) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos para la serie que se está tendiendo. |
| [setForward(double value)](#setForward-double-) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos para la serie que se está tendiendo. |
| [getIntercept()](#getIntercept--) | Especifica el valor donde la línea de tendencia cruzará el eje y. |
| [setIntercept(double value)](#setIntercept-double-) | Especifica el valor donde la línea de tendencia cruzará el eje y. |
| [getDisplayEquation()](#getDisplayEquation--) | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor Rsquaredvalue). |
| [getOrder()](#getOrder--) | Especifica el orden de la línea de tendencia polinómica. |
| [setOrder(byte value)](#setOrder-byte-) | Especifica el orden de la línea de tendencia polinómica. |
| [getPeriod()](#getPeriod--) | Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. |
| [setPeriod(byte value)](#setPeriod-byte-) | Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Especifica que el valor R-squared de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Especifica que el valor R-squared de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa la entrada de leyenda relacionada con esta línea de tendencia Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding con el texto en el parámetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Puede contener un texto con formato enriquecido. |
| [getTextFormat()](#getTextFormat--) | Devuelve el formato de texto. |
| [getChart()](#getChart--) | Devuelve el gráfico padre. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre de un FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Obtiene o establece el nombre de la línea de tendencia. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Obtiene o establece el nombre de la línea de tendencia. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Obtiene o establece el tipo de línea de tendencia. Lectura/escritura [TrendlineType](../../com.aspose.slides/trendlinetype).

**Devuelve:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Obtiene o establece el tipo de línea de tendencia. Lectura/escritura [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representa el formato de la línea de tendencia. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representa el formato de la línea de tendencia. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos para la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Lectura/escritura double.

**Devuelve:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos para la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos para la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Lectura/escritura double.

**Devuelve:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos para la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Especifica el valor donde la línea de tendencia cruzará el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Lectura/escritura double.

**Devuelve:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Especifica el valor donde la línea de tendencia cruzará el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor Rsquaredvalue). Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor Rsquaredvalue). Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Lectura/escritura byte.

**Devuelve:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Lectura/escritura byte.

**Devuelve:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Especifica que el valor R-squared de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Especifica que el valor R-squared de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representa la entrada de leyenda relacionada con esta línea de tendencia Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializa TextFrameForOverriding con el texto en el parámetro "text". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto.

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

Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, este valor de texto formateado sobrescribe el texto generado automáticamente de la etiqueta de datos. El texto generado automáticamente de la etiqueta de datos significa el texto que es gestionado por las propiedades ShowSeriesName, ShowValue, … y que está formateado con la propiedad TextFormatManager.TextFormat. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Devuelve el formato de texto. Solo lectura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Devuelve:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico padre. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)
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