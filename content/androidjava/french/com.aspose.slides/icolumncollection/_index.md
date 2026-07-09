---
title: IColumnCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente la collection de colonnes d'un tableau.
type: docs
url: /fr/com.aspose.slides/icolumncollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Représente la collection de colonnes d’un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie la colonne à l’index spécifié. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Crée une copie de la ligne modèle spécifiée et l’insère en bas du tableau. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Crée une copie de la colonne modèle spécifiée et l’insère à la position indiquée dans le tableau. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Supprime une colonne à la position indiquée d’un tableau. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Renvoie la colonne à l’index spécifié. Lecture seule [IColumn](../../com.aspose.slides/icolumn).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Valeur de retour :**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Crée une copie de la ligne modèle spécifiée et l’insère en bas du tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonne utilisée comme modèle. |
| withAttachedColumns | boolean | Vrai pour copier également toutes les colonnes attachées à la ligne modèle. |

**Valeur de retour :**
com.aspose.slides.IColumn[] - Colonnes ajoutées.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Crée une copie de la colonne modèle spécifiée et l’insère à la position indiquée dans le tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle colonne. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonne utilisée comme modèle. |
| withAttachedColumns | boolean | Vrai pour copier également toutes les colonnes attachées à la colonne modèle. |

**Valeur de retour :**
com.aspose.slides.IColumn[] - Colonnes insérées.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Supprime une colonne à la position indiquée d’un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Index de la colonne à supprimer. |
| withAttachedRows | boolean | Vrai pour supprimer également toutes les colonnes attachées. |