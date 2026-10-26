---
title: ExcelDataWorkbook
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/exceldataworkbook/
---
## ExcelDataWorkbook classe

 Représente un classeur qui fournit l'accès aux données Excel pour une utilisation générale.
 
### ExcelDataWorkbook {#ExcelDataWorkbook}

| Name | Description |
| --- | --- |
| ExcelDataWorkbook(String) | Initialise une nouvelle instance en utilisant le chemin de fichier spécifié. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin complet du fichier du classeur Excel. |

 **Renvoie :**
ExcelDataWorkbook

 **Erreur**

| Error | Condition |
| --- | --- |
 | FileNotFoundException | Le fichier spécifié n'existe pas. |


---

### ExcelDataWorkbook {#ExcelDataWorkbook}

| Name | Description |
| --- | --- |
| ExcelDataWorkbook(InputStream) | Initialise une nouvelle instance de la classe en utilisant le flux fourni. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Un flux contenant les données du classeur Excel. |

 **Renvoie :**
ExcelDataWorkbook


---

### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, int, int) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et ses coordonnées de cellule. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Indice basé sur zéro de la feuille de calcul. |
| row | int | Indice de ligne basé sur zéro de la cellule. |
| column | int | Indice de colonne basé sur zéro de la cellule. |

 **Renvoie :**
[ExcelDataCell](../exceldatacell)


---

### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (String, int, int) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et ses coordonnées de cellule. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | Le nom de la feuille de calcul. |
| row | int | Indice de ligne basé sur zéro de la cellule. |
| column | int | Indice de colonne basé sur zéro de la cellule. |

 **Renvoie :**
[ExcelDataCell](../exceldatacell)


---

### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (int, String) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et le nom de cellule au format Excel (par ex., "B2"). |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Indice basé sur zéro de la feuille de calcul. |
| cellName | String | La référence de cellule au format Excel (par ex., "A1", "C5"). |

 **Renvoie :**
[ExcelDataCell](../exceldatacell)


---

### getCell {#getCell}

| Name | Description |
| --- | --- |
| getCell (String, String) | Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par ex., "B2"). |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | Le nom de la feuille de calcul. |
| cellName | String | La référence de cellule au format Excel (par ex., "A1", "C5"). |

 **Renvoie :**
[ExcelDataCell](../exceldatacell)


---

### getCells {#getCells}

| Name | Description |
| --- | --- |
| getCells (String, boolean) | Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| formula | String | Une formule ou expression de plage (par ex., "Sheet1!A1:B3") utilisée pour identifier les cellules cibles. |
| skipHiddenCells | boolean | Si vrai, les cellules masquées (par ex., dans des lignes ou colonnes masquées) seront exclues du résultat. |

 **Renvoie :**
ArrayList, List


---

### getChartsFromWorksheet {#getChartsFromWorksheet}

| Name | Description |
| --- | --- |
| getChartsFromWorksheet (String) | Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur Excel. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| worksheetName | String | Le nom de la feuille de calcul où rechercher les graphiques. |

 **Renvoie :**
Dictionary


---

### getWorksheetNames {#getWorksheetNames}

| Name | Description |
| --- | --- |
| getWorksheetNames () | Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel. |

 **Renvoie :**
ArrayList, List


---