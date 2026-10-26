---
title: PortionCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de portions.
type: docs
url: /fr/com.aspose.slides/portioncollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Représente une collection de portions.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Obtient l'élément à l'index spécifié. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Ajoute une Portion à la fin de la collection. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Détermine l'index d'un élément spécifique dans la List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Insère une Portion dans la collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un tableau, en commençant à un indice de tableau particulier. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule.

**Retour :**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. booléen en lecture seule.

**Retour :**
boolean - true si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon, false.

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Ajoute une Portion à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion à ajouter à la fin de la collection. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Détermine l'index d'un élément spécifique dans la List.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'objet à localiser dans la List. |

**Retour :**
int - L'index de l'élément s'il est trouvé dans la liste ; sinon, -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Insère une Portion dans la collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index zéro basé auquel la Portion doit être insérée. |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion à insérer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'objet à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour :**
boolean - true si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un tableau, en commençant à un indice de tableau particulier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'index zéro basé dans le tableau à partir duquel la copie commence. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'objet à supprimer du [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour :**
boolean - true si l'élément a été supprimé avec succès du [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans l'original [IGenericCollection](../../com.aspose.slides/igenericcollection).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Un java.util.Iterator pour l'ensemble de la collection.