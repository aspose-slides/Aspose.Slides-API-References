---
title: IRowCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de lignes de tableau.
type: docs
url: /fr/com.aspose.slides/irowcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Représente une collection de lignes de tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Récupère l'élément à l'indice spécifié. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crée une copie de la ligne modèle spécifiée et l'insère au bas d'une table. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crée une copie de la ligne modèle spécifiée et l'insère à la position spécifiée dans une table. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Supprime une ligne à la position spécifiée d'une table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Récupère l'élément à l'indice spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Crée une copie de la ligne modèle spécifiée et l'insère au bas d'une table.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | True pour copier également toutes les lignes attachées à la ligne modèle. |

**Retour :**
com.aspose.slides.IRow[] - Lignes ajoutées.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Crée une copie de la ligne modèle spécifiée et l'insère à la position spécifiée dans une table.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice d'une nouvelle ligne. |
| templ | [IRow](../../com.aspose.slides/irow) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | True pour copier également toutes les lignes attachées à la ligne modèle. |

**Retour :**
com.aspose.slides.IRow[] - Lignes insérées.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Supprime une ligne à la position spécifiée d'une table.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Indice d'une ligne à supprimer. |
| withAttachedRows | boolean | True pour supprimer également toutes les lignes attachées. |