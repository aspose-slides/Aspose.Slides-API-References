---
title: CustomXmlPartCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de parties XML personnalisées.
type: docs
url: /fr/com.aspose.slides/customxmlpartcollection/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Représente une collection de parties XML personnalisées.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'élément à l'index spécifié. |
| [size()](#size--) | Renvoie le nombre de parties XML personnalisées dans la collection. |
| [add(String xmlString)](#add-java.lang.String-) | Ajoute une nouvelle partie XML personnalisée. |
| [add(byte[] xmlData)](#add-byte---) | Ajoute une nouvelle partie XML personnalisée. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Ajoute une nouvelle partie XML personnalisée. |
| [removeAt(int index)](#removeAt-int-) | Supprime la partie XML personnalisée à l'index spécifié. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie vers le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un itérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l'ensemble de la collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Renvoie l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé à zéro de l'élément à obtenir. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - L'élément à l'index spécifié.

### size() {#size--}
```
public final int size()
```

Renvoie le nombre de parties XML personnalisées dans la collection. **int en lecture seule.**

**Renvoie :**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Ajoute une nouvelle partie XML personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | La chaîne XML de la nouvelle partie à ajouter. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Partie XML personnalisée créée.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Ajoute une nouvelle partie XML personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | Les données XML de la nouvelle partie à ajouter. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Partie XML personnalisée créée.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Ajoute une nouvelle partie XML personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Le flux d'entrée contenant les données XML de la nouvelle partie à ajouter. |

**Renvoie :**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Partie XML personnalisée créée.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime la partie XML personnalisée à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé à zéro de l'élément à supprimer. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La partie XML personnalisée à supprimer. |

**Renvoie :**
boolean - true si l'élément a été supprimé avec succès ; sinon, false.

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie vers le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau de destination. |
| index | int | Index de début de la copie. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). **boolean en lecture seule.**

**Renvoie :**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. **Object en lecture seule.**

**Renvoie :**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Renvoie un itérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Renvoie un itérateur Java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un java.util.Iterator pour l'ensemble de la collection.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. **IDOMObject en lecture seule.**

**Renvoie :**
com.aspose.slides.IDOMObject