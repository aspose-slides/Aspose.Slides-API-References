---
title: BehaviorCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection d'effets de comportement.
type: docs
url: /fr/com.aspose.slides/behaviorcollection/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)  
```
public class BehaviorCollection implements IBehaviorCollection
```

Représente une collection d'effets de comportement.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Renvoie le nombre de comportements dans une collection. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Ajoute un nouveau comportement à une collection. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Détermine l'index d'un élément spécifique dans la List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Insère un nouveau comportement dans une collection à l'index spécifié. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un Array, en commençant à un indice de Array particulier. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Supprime le comportement spécifié d'une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime le comportement d'une collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les comportements d'une collection. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [get_Item(int index)](#get-Item-int-) | Renvoie un comportement à l'index spécifié. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Définit un comportement à l'index spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |

### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre de comportements dans une collection. int en lecture seule.

**Renvoie :**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. booléen en lecture seule.

**Renvoie :**  
booléen - true si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon, false.

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Ajoute un nouveau comportement à une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportement à ajouter. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Détermine l'index d'un élément spécifique dans la List.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'objet à rechercher dans la List. |

**Renvoie :**  
int - L'index de l'élément s'il est trouvé dans la liste ; sinon, -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Insère un nouveau comportement dans une collection à l'index spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index où le nouveau comportement doit être inséré. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportement à insérer. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un Array, en commençant à un indice de Array particulier.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'index de base zéro dans le tableau où la copie commence. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Supprime le comportement spécifié d'une collection.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportement à supprimer. |

**Renvoie :**  
booléen

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime le comportement d'une collection à l'index spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du comportement à supprimer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les comportements d'une collection.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'objet à rechercher dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**  
booléen - true si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Renvoie un comportement à l'index spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du comportement à renvoyer. |

**Renvoie :**  
[IBehavior](../../com.aspose.slides/ibehavior) - Comportement d'animation.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Définit un comportement à l'index spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du comportement à renvoyer. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un java.util.Iterator pour l'ensemble de la collection.