---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Contenedor de niveles de punto de datos.
type: docs
url: /es/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Contenedor de niveles de punto de datos. Aplicado para series Treeamp y Sunburst. La indexación de niveles de punto de datos es basada en cero.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Devuelve el objeto IChartDataPointLevel para el nivel definido. |
| [getCount()](#getCount--) | Devuelve el recuento de niveles de punto de datos. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
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
public abstract int getCount()
```

Devuelve el recuento de niveles de punto de datos.

**Devuelve:**
int