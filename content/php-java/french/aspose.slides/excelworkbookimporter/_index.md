---
title: ExcelWorkbookImporter
second_title: Aspose.Sildes pour PHP via référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/excelworkbookimporter/
---
## ExcelWorkbookImporter classe

Fournit des fonctionnalités pour importer du contenu d’un classeur Excel dans une présentation.

### addChartFromWorkbook {#addChartFromWorkbook}

| Nom | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  int, boolean) | Récupère un graphique du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Le classeur Excel. |
| worksheetName | String | Le nom de la feuille de calcul contenant le graphique. |
| chartIndex | int | L’indice basé sur zéro de la forme de graphique à insérer. Cet indice peut être obtenu en utilisant la méthode IExcelDataWorkbook#getChartsFromWorksheet(String). |
| embedAllWorkbook | boolean | Si vrai, le classeur complet sera intégré dans le graphique ; sinon, seules les données du graphique seront intégrées. |

**Valeur de retour :**
[Chart](../chart)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Déclenchée lorsque l’un des paramètres requis est null, vide, ou si le graphique ne peut pas être trouvé dans le classeur. |

---

### addChartFromWorkbook {#addChartFromWorkbook}

| Nom | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String, boolean) | Récupère un graphique du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Le classeur Excel. |
| worksheetName | String | Le nom de la feuille de calcul contenant le graphique. |
| chartName | String | Le nom du graphique à ajouter. |
| embedAllWorkbook | boolean | Si vrai, le classeur complet sera intégré dans le graphique ; sinon, seules les données du graphique seront intégrées. |

**Valeur de retour :**
[Chart](../chart)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Déclenchée lorsque l’un des paramètres requis est null, vide, ou si le graphique ne peut pas être trouvé dans le classeur. |

---

### addChartFromWorkbook {#addChartFromWorkbook}

| Nom | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String,  boolean) | Récupère un graphique du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbookStream | InputStream | Un flux contenant les données du classeur. |
| worksheetName | String | Le nom de la feuille de calcul contenant le graphique. |
| chartName | String | Le nom du graphique à ajouter. |
| embedAllWorkbook | boolean | Si vrai, le classeur complet sera intégré dans le graphique ; sinon, seules les données du graphique seront intégrées. |

**Valeur de retour :**
[Chart](../chart)

**Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Déclenchée lorsque les données d’entrée sont dans un format non pris en charge. |

---

### addChartFromWorkbook {#addChartFromWorkbook}

| Nom | Description |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String,  boolean) | Récupère un graphique du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le graphique sera ajouté. |
| x | float | La coordonnée X pour positionner le graphique. |
| y | float | La coordonnée Y pour positionner le graphique. |
| workbookPath | String | Le chemin du fichier vers le classeur contenant le graphique. |
| worksheetName | String | Le nom de la feuille de calcul contenant le graphique. |
| chartName | String | Le nom du graphique à ajouter. |
| embedWorkbook | boolean | Si vrai, le classeur sera intégré dans le graphique ; sinon, le graphique sera lié au classeur externe. |

**Valeur de retour :**
[Chart](../chart)

**Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Déclenchée lorsque les données d’entrée sont dans un format non pris en charge. |

---

### addTableFromWorkbook {#addTableFromWorkbook}

| Nom | Description |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String) | Récupère un tableau du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | float | La coordonnée X pour positionner le tableau. |
| y | float | La coordonnée Y pour positionner le tableau. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Le classeur Excel. |
| worksheetName | String | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | String | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

**Valeur de retour :**
[Table](../table)

**Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Déclenchée lorsque les données d’entrée sont dans un format non pris en charge. |

---

### addTableFromWorkbook {#addTableFromWorkbook}

| Nom | Description |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String) | Récupère un tableau du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | float | La coordonnée X pour positionner le tableau. |
| y | float | La coordonnée Y pour positionner le tableau. |
| workbookPath | String | Le chemin du fichier vers le classeur Excel. |
| worksheetName | String | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | String | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

**Valeur de retour :**
[Table](../table)

**Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Déclenchée lorsque les données d’entrée sont dans un format non pris en charge. |

---

### addTableFromWorkbook {#addTableFromWorkbook}

| Nom | Description |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String) | Récupère un tableau du classeur Excel spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | La collection de formes à laquelle le tableau sera ajouté. |
| x | float | La coordonnée X pour positionner le tableau. |
| y | float | La coordonnée Y pour positionner le tableau. |
| workbookStream | InputStream | Un flux contenant les données du classeur. |
| worksheetName | String | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | String | La plage de cellules qui définit le tableau (par exemple, "A1:D10"). |

**Valeur de retour :**
[Table](../table)

**Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | Déclenchée lorsque les données d’entrée sont dans un format non pris en charge. |