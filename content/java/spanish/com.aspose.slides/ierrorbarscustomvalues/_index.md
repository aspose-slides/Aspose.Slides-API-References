---
title: IErrorBarsCustomValues
second_title: Referencia de la API de Aspose.Slides for Java
description: Especifica los valores de la barra de error.
type: docs
url: /es/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Especifica los valores de la barra de error. It shall be used only when the Error bars value type is Custom.
## Métodos

| Method | Description |
| --- | --- |
| [getXMinus()](#getXMinus--) | Especifica el valor de la barra de error en la dirección negativa. |
| [getYMinus()](#getYMinus--) | Especifica el valor de la barra de error en la dirección negativa. |
| [getXPlus()](#getXPlus--) | Especifica el valor de la barra de error en la dirección positiva. |
| [getYPlus()](#getYPlus--) | Especifica el valor de la barra de error en la dirección positiva. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Especifica el valor de la barra de error en la dirección negativa. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsXFormat. En cualquier otro caso esta propiedad devuelve null. Solo de lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Especifica el valor de la barra de error en la dirección negativa. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsYFormat. En cualquier otro caso esta propiedad devuelve null. Solo de lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Especifica el valor de la barra de error en la dirección positiva. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsXFormat. En cualquier otro caso esta propiedad devuelve null. Solo de lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Especifica el valor de la barra de error en la dirección positiva. Disponible si el tipo de valor de las barras de error es Custom y se permite ErrorBarsYFormat. En cualquier otro caso esta propiedad devuelve null. Solo de lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)