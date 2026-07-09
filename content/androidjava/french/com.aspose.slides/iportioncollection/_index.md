---
title: IPortionCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de portions.
type: docs
url: /fr/com.aspose.slides/iportioncollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Représente une collection de portions.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Ajoute un Portion à la fin de la collection. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Détermine l'index d'une portion spécifique dans la collection. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Insère un Portion dans la collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule.

**Retour :**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Ajoute un Portion à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Le Portion à ajouter à la fin de la collection. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Détermine l'index d'une portion spécifique dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | La portion à localiser dans la collection. |

**Retour :**
int - L'index de l'élément s'il est trouvé dans la collection ; sinon, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Insère un Portion dans la collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de base zéro à laquelle le Portion doit être inséré. |
| value | [IPortion](../../com.aspose.slides/iportion) | Le Portion à insérer. |

### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les éléments de la collection.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'objet à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour :**
booléen - true si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'objet à supprimer du [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour :**
booléen - true si l'élément a été supprimé avec succès du [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) d'origine.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime l'élément à l'index spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de base zéro de l'élément à supprimer. |