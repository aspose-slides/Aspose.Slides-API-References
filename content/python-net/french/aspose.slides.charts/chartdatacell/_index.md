---
title: ChartDataCell class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdatacell/
---
## ChartDataCell classe

Représente une cellule pour les données du graphique.

Le type ChartDataCell expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`row`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/row/) | Renvoie l'index de la ligne de la feuille de calcul dans laquelle la cellule est située.<br/>            Lecture seule **int**. |
| [`column`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/column/) | Renvoie l'index de la colonne de la feuille de calcul dans laquelle la cellule est située.<br/>            Lecture seule **int**. |
| [`value`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/value/) | Obtient ou définit la valeur d'une cellule.<br/>            Lecture/écriture **any**. |
| [`formula`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/formula/) | Obtient ou définit la formule au format A1. |
| [`r1c1_formula`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/r1c1_formula/) | Obtient ou définit la formule au format R1C1. |
| [`chart_data_worksheet`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | Obtient la feuille de calcul.<br/>            Lecture seule [`IChartDataWorksheet`](/slides/python-net/fr/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/is_hidden/) | Détermine si la cellule est masquée.<br/>            Lecture seule **bool**. |
| [`custom_number_format`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/custom_number_format/) | Obtient ou définit le format d'affichage personnalisé des nombres et des dates.<br/>            Si la valeur est vide, le format PresetNumberFormat sera utilisé.<br/>            Lecture/écriture **str**. |
| [`preset_number_format`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/preset_number_format/) | Obtient ou définit le format d'affichage intégré des nombres et des dates. Le numéro prédéfini doit être dans [0..22] ou [37..49].<br/>            Lecture/écriture **int**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/fr/aspose.slides.charts/chartdatacell/calculate/#bool) | Si la cellule contient une formule, la valeur sera mise à jour en fonction de cette formule. |


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)