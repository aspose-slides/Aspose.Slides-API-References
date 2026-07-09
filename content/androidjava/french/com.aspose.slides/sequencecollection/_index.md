---
title: SequenceCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de séquences interactives.
type: docs
url: /fr/com.aspose.slides/sequencecollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
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
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre d'éléments dans une collection Lecture seule int.

**Retour:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Ajoute une nouvelle séquence interactive. Lecture/écriture [Sequence](../../com.aspose.slides/sequence).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Retour:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Supprime la séquence spécifiée d'une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Séquence à supprimer. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime la séquence à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la séquence à supprimer. |
### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les séquences d'une collection.
### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Renvoie une séquence à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Retour:**
[ISequence](../../com.aspose.slides/isequence) - L'objet [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Un java.util.Iterator pour l'ensemble de la collection.