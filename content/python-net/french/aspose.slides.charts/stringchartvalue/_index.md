---
title: StringChartValue class
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides.charts/stringchartvalue/
---
## StringChartValue classe

Représente une valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières :
1) dans la ou les cellules du classeur lié au graphique ;
2) en tant que valeur littérale.

**Héritage:**[`StringChartValue`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/fr/aspose.slides.charts/basechartvalue)

Le type StringChartValue expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`data_source_type`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue/data_source_type/) | Indique si AsCell, AsCells, AsLiteralString ou AsLiteralDouble <br/>            la propriété est effective dans les descendants. En d’autres termes, elle indique le type <br/>            de valeur de la propriété Data.<br/>            Lecture/écriture [`DataSourceType`](/slides/python-net/fr/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue/data/) | Renvoie ou définit l'objet Data.<br/>            Lecture/écriture **any**. |
| [`as_cells`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue/as_cells/) | L’affectation d’une valeur nulle n’est pas autorisée.<br/>            La valeur retournée n’est jamais None.<br/>            Lecture/écriture [`IChartCellCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue/as_literal_string/) | Renvoie ou définit la valeur en tant que chaîne littérale.<br/>            Lecture/écriture **str**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Définit la valeur à partir de la cellule spécifiée. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Si la propriété DataSourceType est DataSourceType.Worksheet alors cette méthode renvoie l’adresse<br/>            des cellules du classeur qui représentent les données de chaîne. Sinon, retourner<br/>            une chaîne vide. |

### Voir aussi
* classe [`BaseChartValue`](/slides/python-net/fr/aspose.slides.charts/basechartvalue)
* classe [`StringChartValue`](/slides/python-net/fr/aspose.slides.charts/stringchartvalue)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)