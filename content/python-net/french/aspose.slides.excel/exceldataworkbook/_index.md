---
title: ExcelDataWorkbook class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook classe

Représente un classeur qui fournit un accès aux données Excel pour une utilisation générale.

Le type ExcelDataWorkbook expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/__init__/#str) | Initialise une nouvelle instance en utilisant le chemin de fichier spécifié. |
| [`__init__(self, stream)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Initialise une nouvelle instance de la classe en utilisant le flux fourni. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et ses coordonnées de cellule. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et ses coordonnées de cellule. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et le nom de cellule au format Excel (par ex., "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par ex., "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Récupère une collection de cellules du classeur correspondant à la formule spécifiée. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/fr/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel. |


### Voir aussi
* module [`aspose.slides.excel`](/slides/python-net/fr/aspose.slides.excel)
* bibliothèque [`Aspose.Slides`](/slides/python-net)