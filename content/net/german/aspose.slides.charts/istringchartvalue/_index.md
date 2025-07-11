---
title: IStringChartValue
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Zeichenfolgenwert dar, der auf zwei Arten in einem pptx-Präsentationsdokument gespeichert werden kann 1 in Zelle/n des Arbeitsblatts, die mit dem Diagramm verbunden sind; 2 als Literalwert.
type: docs
weight: 2140
url: /de/aspose.slides.charts/istringchartvalue/
---

## IStringChartValue-Schnittstelle

Stellt einen Zeichenfolgenwert dar, der auf zwei Arten in einem pptx-Präsentationsdokument gespeichert werden kann: 1) in Zelle/n des Arbeitsblatts, die mit dem Diagramm verbunden sind; 2) als Literalwert.

```csharp
public interface IStringChartValue : IMultipleCellChartValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMultipleCellChartValue](../../aspose.slides.charts/istringchartvalue/asimultiplecellchartvalue) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IMultipleCellChartValue. Nur-Lese [`IMultipleCellChartValue`](../imultiplecellchartvalue). |
| [AsLiteralString](../../aspose.slides.charts/istringchartvalue/asliteralstring) { get; set; } | Gibt die Literalzeichenfolge zurück oder legt sie fest, wenn die Eigenschaft DataSourceType DataSourceType.StringLiterals ist. Lese-/Schreibzeichenfolge. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetCellsAddressInWorkbook](../../aspose.slides.charts/istringchartvalue/getcellsaddressinworkbook)() | Wenn die Eigenschaft DataSourceType DataSourceType.Worksheet ist, gibt diese Methode die Adresse der Zellen im Arbeitsblatt zurück, die die Zeichendaten darstellen. Andernfalls wird eine leere Zeichenfolge zurückgegeben. |
| [SetFromOneCell](../../aspose.slides.charts/istringchartvalue/setfromonecell)(IChartDataCell) | Setzt den Wert aus der angegebenen Zelle. |
| [ToString](../../aspose.slides.charts/istringchartvalue/tostring)() | Gibt die Zeichenfolgenrepräsentation zurück. |

### Siehe auch

* Schnittstelle [IMultipleCellChartValue](../imultiplecellchartvalue)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->