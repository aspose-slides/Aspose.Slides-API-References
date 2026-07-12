---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: Especifica los valores de la barra de error.
type: docs
url: /es/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Especifica los valores de la barra de error. Sólo debe usarse cuando el tipo de valor de las barras de error es Custom.
## Métodos

| Método | Descripción |
| --- | --- |
| [getXMinus()](#getXMinus--) | Especifica el valor de la barra de error en la dirección negativa. |
| [getYMinus()](#getYMinus--) | Especifica el valor de la barra de error en la dirección negativa. |
| [getXPlus()](#getXPlus--) | Especifica el valor de la barra de error en la dirección positiva. |
| [getYPlus()](#getYPlus--) | Especifica el valor de la barra de error en la dirección positiva. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Especifica el valor de la barra de error en la dirección negativa. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsXFormat. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Especifica el valor de la barra de error en la dirección negativa. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsYFormat. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Especifica el valor de la barra de error en la dirección positiva. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsXFormat. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Especifica el valor de la barra de error en la dirección positiva. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsYFormat. En cualquier otro caso esta propiedad devuelve null. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)