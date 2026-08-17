---
title: IRowCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente la collection de lignes de tableau.
type: docs
url: /fr/com.aspose.slides/irowcollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Représente la collection de lignes de tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crée une copie de la ligne modèle spécifiée et l'insère en bas d'un tableau. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crée une copie de la ligne modèle spécifiée et l'insère à la position spécifiée dans un tableau. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Supprime une ligne à la position spécifiée d'un tableau. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Obtient l'élément à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Crée une copie de la ligne modèle spécifiée et l'insère en bas d'un tableau.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | Vrai pour copier également toutes les lignes attachées à la ligne modèle. |

**Renvoie:**
com.aspose.slides.IRow[] - Lignes ajoutées.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Crée une copie de la ligne modèle spécifiée et l'insère à la position spécifiée dans un tableau.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une nouvelle ligne. |
| templ | [IRow](../../com.aspose.slides/irow) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | Vrai pour copier également toutes les lignes attachées à la ligne modèle. |

**Renvoie:**
com.aspose.slides.IRow[] - Lignes insérées.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Supprime une ligne à la position spécifiée d'un tableau.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index d'une ligne à supprimer. |
| withAttachedRows | boolean | Vrai pour supprimer également toutes les lignes attachées. |