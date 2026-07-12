---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Contenedor de niveles de puntos de datos.
type: docs
url: /es/com.aspose.slides/chartdatapointlevelsmanager/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Contenedor de niveles de puntos de datos. Aplicado a series Treeamp y Sunburst. La indexación de los niveles de puntos de datos comienza en cero.

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Devuelve el objeto IChartDataPointLevel para el nivel definido. |
| [getCount()](#getCount--) | Devuelve el recuento de niveles de puntos de datos. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

Devuelve el objeto IChartDataPointLevel para el nivel definido.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level | int |  |

**Devuelve:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

Devuelve el recuento de niveles de puntos de datos.

**Devuelve:**
int