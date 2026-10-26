---
title: ITrendline
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Clase que representa la línea de tendencia de una serie de gráficos
type: docs
url: /es/com.aspose.slides/itrendline/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Clase que representa la línea de tendencia de una serie de gráficos
## Métodos

| Método | Descripción |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Obtiene o establece el nombre de la línea de tendencia. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Obtiene o establece el nombre de la línea de tendencia. |
| [getTrendlineType()](#getTrendlineType--) | Obtiene o establece el tipo de línea de tendencia. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Obtiene o establece el tipo de línea de tendencia. |
| [getFormat()](#getFormat--) | Representa el formato de la línea de tendencia. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa el formato de la línea de tendencia. |
| [getBackward()](#getBackward--) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. |
| [setBackward(double value)](#setBackward-double-) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. |
| [getForward()](#getForward--) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. |
| [setForward(double value)](#setForward-double-) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. |
| [getIntercept()](#getIntercept--) | Especifica el valor donde la línea de tendencia cruzará el eje y. |
| [setIntercept(double value)](#setIntercept-double-) | Especifica el valor donde la línea de tendencia cruzará el eje y. |
| [getDisplayEquation()](#getDisplayEquation--) | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor de Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor de Rsquaredvalue). |
| [getOrder()](#getOrder--) | Especifica el orden de la línea de tendencia polinómica. |
| [setOrder(byte value)](#setOrder-byte-) | Especifica el orden de la línea de tendencia polinómica. |
| [getPeriod()](#getPeriod--) | Especifica el período de la línea de tendencia para una línea de tendencia de promedio móvil. |
| [setPeriod(byte value)](#setPeriod-byte-) | Especifica el período de la línea de tendencia para una línea de tendencia de promedio móvil. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Especifica que el valor R al cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Especifica que el valor R al cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa la entrada de leyenda relacionada con esta línea de tendencia Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Obtiene o establece el nombre de la línea de tendencia. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Obtiene o establece el nombre de la línea de tendencia. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Obtiene o establece el tipo de línea de tendencia. Lectura/escritura [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Devuelve:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Obtiene o establece el tipo de línea de tendencia. Lectura/escritura [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa el formato de la línea de tendencia. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa el formato de la línea de tendencia. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor deberá ser cualquier valor no negativo. Lectura/escritura double.

**Devuelve:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor deberá ser cualquier valor no negativo. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor deberá ser cualquier valor no negativo. Lectura/escritura double.

**Devuelve:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor deberá ser cualquier valor no negativo. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Especifica el valor donde la línea de tendencia cruzará el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Lectura/escritura double.

**Devuelve:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Especifica el valor donde la línea de tendencia cruzará el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor de Rsquaredvalue). Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el valor de Rsquaredvalue). Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Lectura/escritura byte.

**Devuelve:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Especifica el período de la línea de tendencia para una línea de tendencia de promedio móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Lectura/escritura byte.

**Devuelve:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Especifica el período de la línea de tendencia para una línea de tendencia de promedio móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Especifica que el valor R al cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Especifica que el valor R al cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representa la entrada de leyenda relacionada con esta línea de tendencia Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)