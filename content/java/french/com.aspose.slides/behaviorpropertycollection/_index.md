---
title: BehaviorPropertyCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés de synchronisation pour le comportement de l'effet.
type: docs
url: /fr/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Représente les propriétés de synchronisation pour le comportement de l'effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre de propriétés stockées dans la collection. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Ajoute une nouvelle propriété à la collection. |
| [add(String propertyValue)](#add-java.lang.String-) | Ajoute une nouvelle propriété à la collection. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Détermine l'index d'un élément spécifique dans la List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Détermine l'index d'un élément spécifique par valeur de propriété dans la List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Insère une nouvelle propriété dans la collection à l'index spécifié. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Insère une nouvelle propriété (avec la valeur de propriété spécifiée) dans la collection à l'index spécifié. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un Array, en commençant à un indice d'Array particulier. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Supprime la propriété spécifiée de la collection. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Supprime la propriété spécifiée de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime la propriété à l'index spécifié. |
| [clear()](#clear--) | Supprime toutes les propriétés de la collection. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [get_Item(int index)](#get-Item-int-) | Renvoie une propriété à l'index spécifié. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Définit une propriété à l'index spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```


Renvoie le nombre de propriétés stockées dans la collection. Lecture seule int.

**Retour:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. Lecture seule boolean.

**Retour:**
boolean - vrai si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon, faux.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Ajoute une nouvelle propriété à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propriété à ajouter. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Ajoute une nouvelle propriété à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Valeur de la propriété à ajouter. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Détermine l'index d'un élément spécifique dans la List.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | L'objet à localiser dans la List. |

**Retour:**
int - L'index de l'élément s'il est trouvé dans la liste ; sinon, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Détermine l'index d'un élément spécifique par valeur de propriété dans la List.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | valeur de la propriété |

**Retour:**
int - L'index de la propriété avec la valeur spécifiée
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Insère une nouvelle propriété dans la collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index où une nouvelle propriété doit être insérée. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propriété à ajouter. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Insère une nouvelle propriété (avec la valeur de propriété spécifiée) dans la collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index où une nouvelle propriété doit être insérée. |
| propertyValue | java.lang.String | Valeur de la propriété à ajouter. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un Array, en commençant à un indice d'Array particulier.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'indice de base zéro dans le tableau à partir duquel la copie commence. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Supprime la propriété spécifiée de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propriété à supprimer. |

**Retour:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


Supprime la propriété spécifiée de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Valeur de la propriété à supprimer. |

**Retour:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime la propriété à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la propriété qui doit être supprimée. |

### clear() {#clear--}
```
public final void clear()
```


Supprime toutes les propriétés de la collection.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | La propriété à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - vrai si l'élément est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, faux.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Valeur de la propriété à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - vrai si la valeur de la propriété est trouvée dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, faux.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Renvoie une propriété à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une propriété à renvoyer. |

**Retour:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - propriété de comportement d'animation.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Définit une propriété à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une propriété à renvoyer. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator that can be used to iterate through the collection.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retour:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retour:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retour:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Un java.util.Iterator pour l'ensemble de la collection.