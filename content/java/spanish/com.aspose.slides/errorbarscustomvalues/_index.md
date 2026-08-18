---
title: ErrorBarsCustomValues
second_title: Referencia de la API de Java de Aspose.Slides
description: Especifica los valores de las barras de error.
type: docs
url: /es/com.aspose.slides/errorbarscustomvalues/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

Especifica los valores de las barras de error. Sólo debe usarse cuando el tipo de valor de las barras de error es Custom.
## Métodos

| Método | Descripción |
| --- | --- |
| [getXMinus()](#getXMinus--) | Especifica el valor de la barra de error en la dirección negativa. |
| [getYMinus()](#getYMinus--) | Especifica el valor de la barra de error en la dirección negativa. |
| [getXPlus()](#getXPlus--) | Especifica el valor de la barra de error en la dirección positiva. |
| [getYPlus()](#getYPlus--) | Especifica el valor de la barra de error en la dirección positiva. |
### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```

Especifica el valor de la barra de error en la dirección negativa. Disponible si el tipo de valor de las barras de error es Custom y ErrorBarsXFormat está permitido. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```

Especifica el valor de la barra de error en la dirección negativa. Disponible si el tipo de valor de las barras de error es Custom y ErrorBarsYFormat está permitido. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```

Especifica el valor de la barra de error en la dirección positiva. Disponible si el tipo de valor de las barras de error es Custom y ErrorBarsXFormat está permitido. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```

Especifica el valor de la barra de error en la dirección positiva. Disponible si el tipo de valor de las barras de error es Custom y ErrorBarsYFormat está permitido. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)