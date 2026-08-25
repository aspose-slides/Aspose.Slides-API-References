---
title: ColumnCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/columncollection/
---
## ColumnCollection classe

 Représente une collection de colonnes dans un tableau.
 
### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Column](../column), boolean) | Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| templ | [Column](../column) | Colonne utilisée comme modèle. |
| withAttachedColumns | boolean | True pour copier également toutes les colonnes attachées à la ligne modèle. |

 **Renvoie:**
[Column](../column)

---

### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Lecture seule Object. |

 **Renvoie:**
Object

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie la colonne à l'index spécifié. Lecture seule Column. |

 **Renvoie:**
[Column](../column)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Column](../column), boolean) | Crée une copie de la colonne modèle spécifiée et l'insère à la position indiquée dans un tableau. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index d'une nouvelle colonne. |
| templ | [Column](../column) | Colonne utilisée comme modèle. |
| withAttachedColumns | boolean | True pour copier également toutes les colonnes attachées à la colonne modèle. |

 **Renvoie:**
[Column](../column)

---

### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |

 **Renvoie:**
boolean

---

### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un itérateur qui parcourt la collection. |

 **Renvoie:**

---

### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur Java pour l'ensemble de la collection. |

 **Renvoie:**

---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int, boolean) | Supprime une colonne à la position spécifiée d'un tableau. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Indice de la colonne à supprimer. |
| withAttachedRows | boolean | True pour supprimer également toutes les colonnes attachées. |

 **Renvoie:**
void

---

### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie le nombre de colonnes dans une collection. Lecture seule int. |

 **Renvoie:**
int

---