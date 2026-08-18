---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /es/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Especifica la posición real de un elemento de gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getActualX()](#getActualX--) | Especifica la ubicación real en x (izquierda) del elemento de gráfico respecto a la esquina superior izquierda del gráfico. |
| [getActualY()](#getActualY--) | Especifica la parte superior real del elemento de gráfico respecto a la esquina superior izquierda del gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica el ancho real del elemento de gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica la altura real del elemento de gráfico. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Especifica la ubicación real en x (izquierda) del elemento de gráfico respecto a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer float.

**Devuelve:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Especifica la parte superior real del elemento de gráfico respecto a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer float.

**Devuelve:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Especifica el ancho real del elemento de gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer float.

**Devuelve:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Especifica la altura real del elemento de gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Leer float.

**Devuelve:**
float