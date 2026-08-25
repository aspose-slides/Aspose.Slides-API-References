---
title: RowCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/rowcollection/
---
## RowCollection classe

 Représente la collection de lignes de tableau.

### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Row](../row), boolean) | Crée une copie de la ligne modèle spécifiée et l'insère en bas d'un tableau. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| templ | [Row](../row) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | True pour copier également toutes les lignes attachées à la ligne modèle. |

 **Retour:**
[Row](../row)

---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet en lecture seule. |

 **Retour:**
Object

---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Renvoie la ligne à l'index spécifié. Ligne en lecture seule. |

 **Retour:**
[Row](../row)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Row](../row), boolean) | Crée une copie de la ligne modèle spécifiée et l'insère à la position indiquée dans un tableau. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index d'une nouvelle ligne. |
| templ | [Row](../row) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | True pour copier également toutes les lignes attachées à la ligne modèle. |

 **Retour:**
[Row](../row)

---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). booléen en lecture seule. |

 **Retour:**
boolean

---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

 **Retour:**



---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int, boolean) | Supprime une ligne à la position spécifiée d'un tableau. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index d'une ligne à supprimer. |
| withAttachedRows | boolean | True pour supprimer également toutes les lignes attachées. |

 **Retour:**
void

---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Obtient le nombre de lignes réellement contenues dans la collection. int en lecture seule. |

 **Retour:**
int

---