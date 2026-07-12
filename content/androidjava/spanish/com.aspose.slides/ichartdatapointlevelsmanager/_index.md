---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides para Android vía referencia de API de Java
description: Contenedor de niveles de punto de datos.
type: docs
url: /es/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Contenedor de niveles de punto de datos. Aplicado a series Treeamp y Sunburst. La indexación de los niveles de punto de datos comienza en cero.
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