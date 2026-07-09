---
title: ISequenceCollection
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente une collection de séquences interactives.
type: docs
url: /fr/com.aspose.slides/isequencecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Représente une collection de séquences interactives.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Renvoie le nombre d'éléments dans une collection Lecture seule int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Ajoute une nouvelle séquence interactive. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Supprime la séquence spécifiée d'une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime la séquence à l'index spécifié. |
| [clear()](#clear--) | Supprime toutes les séquences d'une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie une séquence à l'index spécifié. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Renvoie le nombre d'éléments dans une collection Lecture seule int.

**Renvoie :**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Ajoute une nouvelle séquence interactive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Objet Shape [IShape](../../com.aspose.slides/ishape) |

**Renvoie :**
[ISequence](../../com.aspose.slides/isequence) - Nouvelle séquence [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Supprime la séquence spécifiée d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Séquence à supprimer. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime la séquence à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément dans la collection int |
### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les séquences d'une collection.
### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Renvoie une séquence à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Renvoie :**
[ISequence](../../com.aspose.slides/isequence) - L'objet [ISequence](../../com.aspose.slides/isequence).