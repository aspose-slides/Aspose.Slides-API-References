---
title: TagCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente la collection d'étiquettes, paires de chaînes définies par l'utilisateur
type: docs
url: /fr/com.aspose.slides/tagcollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Représente la collection d'étiquettes (paires de chaînes définies par l'utilisateur)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns a number of tags in the collectoin. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a new tag to collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes the tag with a specified name from the collection. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Returns the zero-based index of the specified key in the collection. |
| [contains(String name)](#contains-java.lang.String-) | Determines whether the collection contains a specific name. |
| [removeAt(int index)](#removeAt-int-) | Removes the tag at the specified index. |
| [clear()](#clear--) | Removes all tags from the collection. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Returns value of a tag at the specified index. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Returns key of a tag at the specified index. |
| [getNamesOfTags()](#getNamesOfTags--) | Returns names of tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets a key and a value pair of a tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets a key and a value pair of a tag. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection into the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

Returns a number of tags in the collectoin. Read-only int.

**Returns:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Ajoute une nouvelle étiquette à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de l'étiquette. |
| value | java.lang.String | La valeur de l'étiquette. |

**Renvoie :**
int - L'index de l'étiquette ajoutée.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Supprime l'étiquette avec un nom spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de l'étiquette à supprimer. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Renvoie l'index de base zéro de la clé spécifiée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom à rechercher dans la collection. |

**Renvoie :**
int - L'index de base zéro de la clé, si la clé est trouvée dans la collection ; sinon, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Détermine si la collection contient un nom spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | La clé à localiser. |

**Renvoie :**
boolean - true si la collection contient une étiquette avec la clé spécifiée ; sinon, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Removes the tag at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the tag to remove. |

### clear() {#clear--}
```
public final void clear()
```

Removes all tags from the collection.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Renvoie la valeur d'une étiquette à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'étiquette à renvoyer. |

**Renvoie :**
java.lang.String - Valeur d'une étiquette.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Renvoie la clé d'une étiquette à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'étiquette à renvoyer. |

**Renvoie :**
java.lang.String - Clé d'une étiquette.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Renvoie les noms des étiquettes.

**Returns:**
java.lang.String[] - Noms des étiquettes.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Returns or sets a key and a value pair of a tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Key of a tag. |

**Returns:**
java.lang.String - Value of a tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Returns or sets a key and a value pair of a tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Key of a tag. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau à remplir. |
| index | int | Position de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Objet en lecture seule.

**Renvoie :**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()


Renvoie un itérateur java pour l'ensemble de la collection.

**Retourne:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Un java.util.Iterator pour l'ensemble de la collection.