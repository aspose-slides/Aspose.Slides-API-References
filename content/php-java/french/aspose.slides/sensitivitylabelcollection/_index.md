---
title: SensitivityLabelCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/sensitivitylabelcollection/
---
## SensitivityLabelCollection classe

 Représente une collection d'étiquettes de sensibilité appliquées au document.
 
### add {#add}

| Nom | Description |
| --- | --- |
| add (String, UUID, boolean, int) | Ajoute l'étiquette de sensibilité à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| id | String | L'identifiant de l'étiquette de sensibilité. |
| siteId | UUID | L'identifiant du site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Indicateur indiquant si l'étiquette de sensibilité est activée. |
| methodType | int | Méthode d'attribution pour l'étiquette de sensibilité. |

 **Retour :**
[SensitivityLabel](../sensitivitylabel)


---


### add {#add}

| Nom | Description |
| --- | --- |
| add ([SensitivityLabel](../sensitivitylabel)) | Ajoute une SensitivityLabel à la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| label | [SensitivityLabel](../sensitivitylabel) | L'objet SensitivityLabel à ajouter à la fin de la collection. |

 **Retour :**
int

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Thrown when the sensitivity label with the same Id has already been added. |


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les éléments de la collection. |

 **Retour :**
void


---


### copyTo {#copyTo}

| Nom | Description |
| --- | --- |
| copyTo (com.aspose.slides.ISensitivityLabel[], int) | Copie tous les éléments de la collection dans le tableau spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.ISensitivityLabel[] | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |

 **Retour :**
void


---


### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Renvoie le nombre d'éléments dans la collection. Lecture seule int. |

 **Retour :**
int


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie l'étiquette de sensibilité par indice. |

 **Retour :**
[SensitivityLabel](../sensitivitylabel)


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour :**



---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l'étiquette de sensibilité à l'indice spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de l'étiquette de sensibilité à supprimer. |

 **Retour :**
void


---