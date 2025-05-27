---
title: IStringChartValue
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un valor de cadena que se puede almacenar en un documento de presentación pptx de dos maneras: 1 en una celda/celdas de una hoja de cálculo relacionada con el gráfico; 2 como un valor literal.
type: docs
weight: 2140
url: /es/aspose.slides.charts/istringchartvalue/
---

## Interfaz IStringChartValue

Representa un valor de cadena que se puede almacenar en un documento de presentación pptx de dos maneras: 1) en una celda/celdas de una hoja de cálculo relacionada con el gráfico; 2) como un valor literal.

```csharp
public interface IStringChartValue : IMultipleCellChartValue
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMultipleCellChartValue](../../aspose.slides.charts/istringchartvalue/asimultiplecellchartvalue) { get; } | Permite obtener la interfaz base IMultipleCellChartValue. Solo lectura [`IMultipleCellChartValue`](../imultiplecellchartvalue). |
| [AsLiteralString](../../aspose.slides.charts/istringchartvalue/asliteralstring) { get; set; } | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetCellsAddressInWorkbook](../../aspose.slides.charts/istringchartvalue/getcellsaddressinworkbook)() | Si la propiedad DataSourceType es DataSourceType.Worksheet, entonces este método devuelve la dirección de las celdas en la hoja de cálculo que representan los datos de cadena. De lo contrario, devuelve una cadena vacía. |
| [SetFromOneCell](../../aspose.slides.charts/istringchartvalue/setfromonecell)(IChartDataCell) | Establece el valor de la celda especificada. |
| [ToString](../../aspose.slides.charts/istringchartvalue/tostring)() | Devuelve la representación en cadena. |

### También te puede interesar

* interfaz [IMultipleCellChartValue](../imultiplecellchartvalue)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->