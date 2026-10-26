---
title: add_table_from_workbook method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Récupère un tableau à partir du classeur Excel spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

### Renvoie

Le tableau qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | **float** | La coordonnée X pour positionner le tableau. |
| y | **float** | La coordonnée Y pour positionner le tableau. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/iexceldataworkbook) | Le classeur Excel. |
| worksheet_name | **str** | Le nom de la feuille de calcul contenant le tableau. |
| cell_range | **str** | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Déclenchée lorsque tout paramètre requis est None ou vide, ou lorsque la feuille de calcul ou la plage de cellules spécifiée est invalide. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Déclenchée lorsque les données d'entrée sont dans un format non pris en charge. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Récupère un tableau à partir du fichier de classeur Excel spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

### Renvoie

Le tableau qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | **float** | La coordonnée X pour positionner le tableau. |
| y | **float** | La coordonnée Y pour positionner le tableau. |
| workbook_path | **str** | Le chemin du fichier de classeur Excel. |
| worksheet_name | **str** | Le nom de la feuille de calcul contenant le tableau. |
| cell_range | **str** | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Déclenchée lorsque tout paramètre requis est None ou vide, ou lorsque la feuille de calcul ou la plage de cellules spécifiée est invalide. |
| **RuntimeError(Proxy error(IOException))** | Déclenchée lorsqu'une erreur d'E/S se produit lors de l'accès au fichier de classeur. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Déclenchée lorsque les données d'entrée sont dans un format non pris en charge. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Récupère un tableau à partir du fichier de classeur Excel spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

### Renvoie

Le tableau qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | **float** | La coordonnée X pour positionner le tableau. |
| y | **float** | La coordonnée Y pour positionner le tableau. |
| workbook_stream | **io.RawIOBase** | Un flux contenant les données du classeur. |
| worksheet_name | **str** | Le nom de la feuille de calcul contenant le tableau. |
| cell_range | **str** | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Déclenchée lorsque tout paramètre requis est None ou vide, ou lorsque la feuille de calcul ou la plage de cellules spécifiée est invalide. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Déclenchée lorsque les données d'entrée sont dans un format non pris en charge. |



### Voir aussi
* classe [`ExcelWorkbookImporter`](/slides/python-net/fr/aspose.slides.importing/excelworkbookimporter)
* classe [`IExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/iexceldataworkbook)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* classe [`ITable`](/slides/python-net/fr/aspose.slides/itable)
* module [`aspose.slides.importing`](/slides/python-net/fr/aspose.slides.importing)
* bibliothèque [`Aspose.Slides`](/slides/python-net)