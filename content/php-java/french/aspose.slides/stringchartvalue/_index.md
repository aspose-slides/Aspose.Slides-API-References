---
title: StringChartValue
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/stringchartvalue/
---
## StringChartValue classe

Représente la valeur de chaîne qui peut être stockée dans un document de présentation pptx de deux manières :
1) dans la/les cellule(s) du classeur lié au diagramme ;
2) en tant que valeur littérale.

### getAsCells {#getAsCells}

| Nom | Description |
| --- | --- |
| getAsCells () | L'affectation d'une valeur nulle n'est pas autorisée. La valeur retournée n'est jamais nulle. Lecture/écriture IChartCellCollection. |

**Renvoie :**
[ChartCellCollection](../chartcellcollection)

---

### getAsLiteralString {#getAsLiteralString}

| Nom | Description |
| --- | --- |
| getAsLiteralString () | Renvoie ou définit la valeur en tant que chaîne littérale. Lecture/écriture String. |

**Renvoie :**
String

---

### getCellsAddressInWorkbook {#getCellsAddressInWorkbook}

| Nom | Description |
| --- | --- |
| getCellsAddressInWorkbook () | Si la propriété DataSourceType est DataSourceType.Worksheet alors cette méthode renvoie l'adresse des cellules du classeur qui représentent les données de chaîne. Sinon renvoie une chaîne vide. |

**Renvoie :**
String

---

### getData {#getData}

| Nom | Description |
| --- | --- |
| getData () | Renvoie ou définit l'objet Data. Lecture/écriture Object. |

**Renvoie :**
Object

---

### setAsCells {#setAsCells}

| Nom | Description |
| --- | --- |
| setAsCells ([ChartCellCollection](../chartcellcollection)) | L'affectation d'une valeur nulle n'est pas autorisée. La valeur retournée n'est jamais nulle. Lecture/écriture IChartCellCollection. |

**Renvoie :**
void

---

### setAsLiteralString {#setAsLiteralString}

| Nom | Description |
| --- | --- |
| setAsLiteralString (String) | Renvoie ou définit la valeur en tant que chaîne littérale. Lecture/écriture String. |

**Renvoie :**
void

---

### setData {#setData}

| Nom | Description |
| --- | --- |
| setData (Object) | Renvoie ou définit l'objet Data. Lecture/écriture Object. |

**Renvoie :**
void

---

### setFromOneCell {#setFromOneCell}

| Nom | Description |
| --- | --- |
| setFromOneCell ([ChartDataCell](../chartdatacell)) | Définit la valeur à partir de la cellule spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | Cell. |

**Renvoie :**
void

---

### toString {#toString}

| Nom | Description |
| --- | --- |
| toString () | Renvoie les données de valeur de chaîne. Retourne null si DataSourceType est false et aucune valeur de chaîne n'a été assignée. |

**Renvoie :**
String

---