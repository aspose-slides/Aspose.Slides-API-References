---
title: IBehaviorCollection
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente une collection d'effets de comportement.
type: docs
url: /fr/com.aspose.slides/ibehaviorcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Représente une collection d'effets de comportement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie un comportement à l'index spécifié. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Renvoie un comportement à l'index spécifié. |
| [getCount()](#getCount--) | Renvoie le nombre de comportements dans une collection. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Ajoute un nouveau comportement à une collection. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Détermine l'index d'un élément spécifique dans la liste. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Insère un nouveau comportement dans une collection à l'index spécifié. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Supprime le comportement spécifié d'une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un comportement d'une collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les comportements d'une collection. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Renvoie un comportement à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du comportement à renvoyer. |

**Valeur de retour:**
[IBehavior](../../com.aspose.slides/ibehavior) - Comportement d'animation.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Renvoie un comportement à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du comportement à renvoyer. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Renvoie le nombre de comportements dans une collection. Lecture seule int.

**Valeur de retour:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Ajoute un nouveau comportement à une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportement à ajouter. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Détermine l'index d'un élément spécifique dans la liste.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'objet à localiser dans la liste. |

**Valeur de retour:**
int - L'index de l'élément s'il est trouvé dans la liste ; sinon, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Insère un nouveau comportement dans une collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index où le nouveau comportement doit être inséré. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportement à insérer. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Supprime le comportement spécifié d'une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportement à supprimer. |

**Valeur de retour:**
boolean - Vrai si un comportement a été supprimé avec succès boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime un comportement d'une collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du comportement à supprimer. |
### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les comportements d'une collection.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'objet à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Valeur de retour:**
boolean - vrai si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.