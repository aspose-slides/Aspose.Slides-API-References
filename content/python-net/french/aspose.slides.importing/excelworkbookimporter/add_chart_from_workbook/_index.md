---
title: add_chart_from_workbook method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Récupère un diagramme à partir du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

### Valeur de retour

Le diagramme qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le diagramme sera ajouté. |
| x | **float** | La coordonnée X pour positionner le diagramme. |
| y | **float** | La coordonnée Y pour positionner le diagramme. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/iexceldataworkbook) | Le classeur Excel. |
| worksheet_name | **str** | Le nom de la feuille de calcul qui contient le diagramme. |
| chart_index | **int** | L'index basé sur zéro du shape de diagramme à insérer. <br/><br/>            Cet index peut être obtenu en utilisant la méthode **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Si `true`, le classeur complet sera intégré dans le diagramme ; <br/><br/>            si `false`, seules les données du diagramme seront intégrées. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée lorsque tout paramètre requis est None, vide, ou si le diagramme est introuvable dans le classeur. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Récupère un diagramme à partir du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

### Valeur de retour

Le diagramme qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le diagramme sera ajouté. |
| x | **float** | La coordonnée X pour positionner le diagramme. |
| y | **float** | La coordonnée Y pour positionner le diagramme. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/iexceldataworkbook) | Le classeur Excel. |
| worksheet_name | **str** | Le nom de la feuille de calcul qui contient le diagramme. |
| chart_name | **str** | Le nom du diagramme à ajouter. |
| embed_all_workbook | **bool** | Si `true`, le classeur complet sera intégré dans le diagramme ; <br/><br/>            si `false`, seules les données du diagramme seront intégrées. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée lorsque tout paramètre requis est None, vide, ou si le diagramme est introuvable dans le classeur. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Récupère un diagramme à partir du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

### Valeur de retour

Le diagramme qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le diagramme sera ajouté. |
| x | **float** | La coordonnée X pour positionner le diagramme. |
| y | **float** | La coordonnée Y pour positionner le diagramme. |
| workbook_stream | **io.RawIOBase** | Un flux contenant les données du classeur. |
| worksheet_name | **str** | Le nom de la feuille de calcul qui contient le diagramme. |
| chart_name | **str** | Le nom du diagramme à ajouter. |
| embed_all_workbook | **bool** | Si `true`, le classeur complet sera intégré dans le diagramme ; <br/><br/>            si `false`, seules les données du diagramme seront intégrées. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée lorsque tout paramètre requis est None, vide, ou si le diagramme est introuvable dans le classeur. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Levée lorsque les données d'entrée sont dans un format non pris en charge. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Récupère un diagramme à partir du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

### Valeur de retour

Le diagramme qui a été ajouté à la collection de formes.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection) | La collection de formes à laquelle le diagramme sera ajouté. |
| x | **float** | La coordonnée X pour positionner le diagramme. |
| y | **float** | La coordonnée Y pour positionner le diagramme. |
| workbook_path | **str** | Le chemin du fichier vers le classeur contenant le diagramme. |
| worksheet_name | **str** | Le nom de la feuille de calcul qui contient le diagramme. |
| chart_name | **str** | Le nom du diagramme à ajouter. |
| embed_workbook | **bool** | Si `true`, le classeur sera intégré dans le diagramme ; <br/><br/>            si `false`, le diagramme sera lié au classeur externe. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Levée lorsque tout paramètre requis est None, vide, ou si le diagramme est introuvable dans le classeur. |
| **RuntimeError(Proxy error(IOException))** | Levée lorsqu’une erreur d’E/S se produit lors de l’accès au fichier. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Levée lorsque les données d'entrée sont dans un format non pris en charge. |



### Voir aussi
* classe [`ExcelWorkbookImporter`](/slides/python-net/fr/aspose.slides.importing/excelworkbookimporter)
* classe [`IExcelDataWorkbook`](/slides/python-net/fr/aspose.slides.excel/iexceldataworkbook)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* module [`aspose.slides.importing`](/slides/python-net/fr/aspose.slides.importing)
* bibliothèque [`Aspose.Slides`](/slides/python-net)