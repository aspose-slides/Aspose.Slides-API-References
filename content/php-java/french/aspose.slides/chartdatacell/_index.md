---
title: ChartDataCell
second_title: Référence d'API Aspose.Sildes pour PHP via Java
description: 
type: docs

url: /fr/aspose.slides/chartdatacell/
---
## ChartDataCell classe

Représente une cellule pour les données de diagramme.

### calculate {#calculate}

| Name | Description |
| --- | --- |
| calculate (boolean) | Si la cellule contient une formule, la valeur sera mise à jour en fonction de cette formule. |

**Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Si false, aucun calcul réel ne sera effectué. Utilisez true pour vérifier les éventuelles exceptions. |

**Retour:**
void


---


### getChartDataWorksheet {#getChartDataWorksheet}

| Name | Description |
| --- | --- |
| getChartDataWorksheet () | Obtient la feuille de calcul. Lecture seule IChartDataWorksheet. |

**Retour:**
[ChartDataWorksheet](../chartdataworksheet)


---


### getColumn {#getColumn}

| Name | Description |
| --- | --- |
| getColumn () | Renvoie l'index de la colonne de la feuille de calcul dans laquelle la cellule se trouve. Lecture seule int. |

**Retour:**
int


---


### getCustomNumberFormat {#getCustomNumberFormat}

| Name | Description |
| --- | --- |
| getCustomNumberFormat () | Obtient ou définit le format d'affichage personnalisé des nombres et des dates. Si la valeur est vide, la valeur PresetNumberFormat sera utilisée. Lecture/écriture String. |

**Retour:**
String

**Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lancé si la valeur est nulle. |


---


### getFormula {#getFormula}

| Name | Description |
| --- | --- |
| getFormula () | Obtient ou définit la formule au format A1. |

**Retour:**
String


---


### getPresetNumberFormat {#getPresetNumberFormat}

| Name | Description |
| --- | --- |
| getPresetNumberFormat () | Obtient ou définit le format d'affichage intégré des nombres et des dates. Le numéro prédéfini doit être dans [0..22] ou [37..49]. Lecture/écriture byte. |

**Retour:**
byte


---


### getR1C1Formula {#getR1C1Formula}

| Name | Description |
| --- | --- |
| getR1C1Formula () | Obtient ou définit la formule au format R1C1. |

**Retour:**
String


---


### getRow {#getRow}

| Name | Description |
| --- | --- |
| getRow () | Renvoie l'index de la ligne de la feuille de calcul dans laquelle la cellule se trouve. Lecture seule int. |

**Retour:**
int


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue () | Obtient ou définit la valeur d'une cellule. Lecture/écriture Object. |

**Retour:**
Object


---


### isHidden {#isHidden}

| Name | Description |
| --- | --- |
| isHidden () | Détermine si la cellule est masquée. Lecture seule boolean. |

**Retour:**
boolean


---


### setCustomNumberFormat {#setCustomNumberFormat}

| Name | Description |
| --- | --- |
| setCustomNumberFormat (String) | Obtient ou définit le format d'affichage personnalisé des nombres et des dates. Si la valeur est vide, la valeur PresetNumberFormat sera utilisée. Lecture/écriture String. |

**Retour:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lancé si la valeur est nulle. |


---


### setFormula {#setFormula}

| Name | Description |
| --- | --- |
| setFormula (String) | Obtient ou définit la formule au format A1. |

**Retour:**
void


---


### setPresetNumberFormat {#setPresetNumberFormat}

| Name | Description |
| --- | --- |
| setPresetNumberFormat (byte) | Obtient ou définit le format d'affichage intégré des nombres et des dates. Le numéro prédéfini doit être dans [0..22] ou [37..49]. Lecture/écriture byte. |

**Retour:**
void


---


### setR1C1Formula {#setR1C1Formula}

| Name | Description |
| --- | --- |
| setR1C1Formula (String) | Obtient ou définit la formule au format R1C1. |

**Retour:**
void


---


### setValue {#setValue}

| Name | Description |
| --- | --- |
| setValue (Object) | Obtient ou définit la valeur d'une cellule. Lecture/écriture Object. |

**Retour:**
void


---