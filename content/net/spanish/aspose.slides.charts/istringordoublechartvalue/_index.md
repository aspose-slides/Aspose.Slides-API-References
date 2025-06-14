---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides para .NET API Reference
description: Representa un valor de cadena o doble que se puede almacenar en un documento de presentación pptx de dos maneras 1 en celda/celdas de un libro de trabajo relacionado con el gráfico; 2 como valor literal.
type: docs
weight: 2150
url: /es/aspose.slides.charts/istringordoublechartvalue/
---

## Interfaz IStringOrDoubleChartValue

Representa un valor de cadena o doble que se puede almacenar en un documento de presentación pptx de dos maneras: 1) en celda/celdas de un libro de trabajo relacionado con el gráfico; 2) como valor literal.

```csharp
public interface IStringOrDoubleChartValue : ISingleCellChartValue
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISingleCellChartValue](../../aspose.slides.charts/istringordoublechartvalue/asisinglecellchartvalue) { get; } | Permite obtener la interfaz base ISingleCellChartValue. Solo lectura [`ISingleCellChartValue`](../isinglecellchartvalue). |
| [AsLiteralDouble](../../aspose.slides.charts/istringordoublechartvalue/asliteraldouble) { get; set; } | Devuelve o establece el doble literal si la propiedad DataSourceType es DataSourceType.DoubleLiterals. Lectura/escritura Doble. |
| [AsLiteralString](../../aspose.slides.charts/istringordoublechartvalue/asliteralstring) { get; set; } | Devuelve o establece la cadena literal si la propiedad DataSourceType es DataSourceType.StringLiterals. Lectura/escritura Cadena. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ToDouble](../../aspose.slides.charts/istringordoublechartvalue/todouble)() | Convierte el valor a doble. |

### Vea también

* interfaz [ISingleCellChartValue](../isinglecellchartvalue)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->