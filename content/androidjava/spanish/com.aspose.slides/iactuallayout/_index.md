---
title: IActualLayout
second_title: Aspose.Slides para Android mediante la API de Java
description: Especifica la posición real de un elemento del gráfico.
type: docs
url: /es/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Especifica la posición real de un elemento del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getActualX()](#getActualX--) | Especifica la posición x real (izquierda) del elemento del gráfico relativa a la esquina superior izquierda del gráfico. |
| [getActualY()](#getActualY--) | Especifica la parte superior real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica el ancho real del elemento del gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica la altura real del elemento del gráfico. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Especifica la posición x real (izquierda) del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Devuelve:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Especifica la parte superior real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Devuelve:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Especifica el ancho real del elemento del gráfico. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Devuelve:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Especifica la altura real del elemento del gráfico. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Devuelve:**
float