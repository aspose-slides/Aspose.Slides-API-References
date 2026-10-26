---
title: TagCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente la collection d'étiquettes, paires de chaînes définies par l'utilisateur
type: docs
url: /fr/com.aspose.slides/tagcollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
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
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d'étiquettes dans la collection. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Ajoute une nouvelle étiquette à la collection. |
| [remove(String name)](#remove-java.lang.String-) | Supprime l'étiquette portant un nom spécifié de la collection. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Renvoie l'index zéro-based de la clé spécifiée dans la collection. |
| [contains(String name)](#contains-java.lang.String-) | Détermine si la collection contient un nom spécifique. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'étiquette à l'index spécifié. |
| [clear()](#clear--) | Supprime toutes les étiquettes de la collection. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Renvoie la valeur d'une étiquette à l'index spécifié. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Renvoie la clé d'une étiquette à l'index spécifié. |
| [getNamesOfTags()](#getNamesOfTags--) | Renvoie les noms des étiquettes. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit une paire clé/valeur d'une étiquette. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Renvoie ou définit une paire clé/valeur d'une étiquette. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'étiquettes dans la collection. Lecture seule int.

**Renvoie :**
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

Supprime l'étiquette portant un nom spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de l'étiquette à supprimer. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Renvoie l'index zéro-based de la clé spécifiée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom à rechercher dans la collection. |

**Renvoie :**
int - L'index zéro-based de la clé, si la clé est trouvée dans la collection ; sinon, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Détermine si la collection contient un nom spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | La clé à rechercher. |

**Renvoie :**
boolean - True si la collection contient une étiquette avec la clé spécifiée ; sinon, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'étiquette à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index zéro-based de l'étiquette à supprimer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les étiquettes de la collection.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Renvoie la valeur d'une étiquette à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'étiquette à retourner. |

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
| index | int | Index de l'étiquette à retourner. |

**Renvoie :**
java.lang.String - Clé d'une étiquette.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Renvoie les noms des étiquettes.

**Renvoie :**
java.lang.String[] - Noms des étiquettes.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Renvoie ou définit une paire clé/valeur d'une étiquette.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Clé d'une étiquette. |

**Renvoie :**
java.lang.String - Valeur d'une étiquette.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Renvoie ou définit une paire clé/valeur d'une étiquette.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Clé d'une étiquette. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau à remplir. |
| index | int | Position de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Un java.util.Iterator pour l'ensemble de la collection.