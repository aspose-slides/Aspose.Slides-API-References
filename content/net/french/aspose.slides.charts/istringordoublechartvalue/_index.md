---
title: IStringOrDoubleChartValue
second_title: Référence API Aspose.Slides pour .NET
description: Représente une valeur de chaîne ou de double qui peut être stockée dans un document de présentation pptx de deux manières : 1 dans une cellule / cellules du classeur liées au graphique ; 2 en tant que valeur littérale.
type: docs
weight: 2150
url: /fr/aspose.slides.charts/istringordoublechartvalue/
---

## Interface IStringOrDoubleChartValue

Représente une valeur de chaîne ou de double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans une cellule / cellules du classeur liées au graphique ; 2) en tant que valeur littérale.

```csharp
public interface IStringOrDoubleChartValue : ISingleCellChartValue
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsISingleCellChartValue](../../aspose.slides.charts/istringordoublechartvalue/asisinglecellchartvalue) { get; } | Permet d'obtenir l'interface de base ISingleCellChartValue. Lecture seule [`ISingleCellChartValue`](../isinglecellchartvalue). |
| [AsLiteralDouble](../../aspose.slides.charts/istringordoublechartvalue/asliteraldouble) { get; set; } | Renvoie ou définit le double littéral si la propriété DataSourceType est DataSourceType.DoubleLiterals. Lecture/écriture Double. |
| [AsLiteralString](../../aspose.slides.charts/istringordoublechartvalue/asliteralstring) { get; set; } | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals. Lecture/écriture String. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ToDouble](../../aspose.slides.charts/istringordoublechartvalue/todouble)() | Convertit la valeur en double. |

### Voir aussi

* interface [ISingleCellChartValue](../isinglecellchartvalue)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->