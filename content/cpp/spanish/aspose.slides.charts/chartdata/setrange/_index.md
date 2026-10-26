---
title: SetRange()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el rango de datos del gráfico. Las series y categorías se actualizarán basándose en el nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, se agregarán series adicionales con el mismo tipo que la última serie de la colección actual al final de la colección.
type: docs
weight: 170
url: /es/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) método

Establece el rango de datos del gráfico. Las series y categorías se actualizarán en función del nuevo rango de datos. Si la cantidad de series en el rango de datos es mayor que el número de series en los datos del gráfico, se añadirán series adicionales con el mismo tipo que la última serie de la colección actual al final de la colección.

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | La fórmula del rango de datos de las celdas. Por ejemplo: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## Ver también

* Clase [String](../../../system/string/)
* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)