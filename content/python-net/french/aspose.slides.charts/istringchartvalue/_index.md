---
title: IStringChartValue class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue classe

Représente une valeur de chaîne pouvant être stockée dans un document de présentation pptx de deux manières :
1) dans la ou les cellules du classeur lié au graphique ;
2) en tant que valeur littérale.

Le type IStringChartValue expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`as_literal_string`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/as_literal_string/) | Renvoie ou définit la chaîne littérale si la propriété DataSourceType est DataSourceType.StringLiterals.<br/>            Lecture/écriture **str**. |
| [`as_cells`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/data/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`to_string(self)`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/to_string/#) | Renvoie la représentation sous forme de chaîne. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Définit la valeur à partir de la cellule spécifiée. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/fr/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Si la propriété DataSourceType est DataSourceType.Worksheet, alors cette méthode renvoie l’adresse<br/>            des cellules du classeur qui représentent les données de chaîne. Sinon, renvoie<br/>            une chaîne vide. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)