---
title: ITagCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente la collection d'étiquettes (paires de chaînes définies par l'utilisateur)
type: docs
url: /fr/com.aspose.slides/itagcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Représente la collection d'étiquettes (paires de chaînes définies par l'utilisateur)
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Ajoute une nouvelle étiquette à la collection. |
| [remove(String name)](#remove-java.lang.String-) | Supprime l'étiquette portant le nom spécifié de la collection. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Renvoie l'index de base zéro de la clé spécifiée dans la collection. |
| [contains(String name)](#contains-java.lang.String-) | Détermine si la collection contient un nom spécifique. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'étiquette à l'index spécifié. |
| [clear()](#clear--) | Supprime toutes les étiquettes de la collection. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Renvoie la valeur d'une étiquette à l'index spécifié. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Renvoie la clé d'une étiquette à l'index spécifié. |
| [getNamesOfTags()](#getNamesOfTags--) | Renvoie les noms des étiquettes. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit une paire clé/valeur d'une étiquette. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Renvoie ou définit une paire clé/valeur d'une étiquette. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```


Ajoute une nouvelle étiquette à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de l'étiquette. |
| value | java.lang.String | La valeur de l'étiquette. |

**Retour:**
int - L'index de l'étiquette ajoutée.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Supprime l'étiquette portant le nom spécifié de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de l'étiquette à supprimer. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Renvoie l'index de base zéro de la clé spécifiée dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom à rechercher dans la collection. |

**Retour:**
int - L'index de base zéro de la clé, si la clé est trouvée dans la collection ; sinon, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Détermine si la collection contient un nom spécifique.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | La clé à rechercher. |

**Retour:**
boolean - True si la collection contient une étiquette avec la clé spécifiée ; sinon, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime l'étiquette à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de base zéro de l'étiquette à supprimer. |
### clear() {#clear--}
```
public abstract void clear()
```


Supprime toutes les étiquettes de la collection.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Renvoie la valeur d'une étiquette à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'étiquette à renvoyer. |

**Retour:**
java.lang.String - Valeur de l'étiquette.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Renvoie la clé d'une étiquette à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'étiquette à renvoyer. |

**Retour:**
java.lang.String - Clé de l'étiquette.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Renvoie les noms des étiquettes.

**Retour:**
java.lang.String[] - Noms des étiquettes.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Renvoie ou définit une paire clé/valeur d'une étiquette.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Clé de l'étiquette. |

**Retour:**
java.lang.String - Valeur de l'étiquette.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Renvoie ou définit une paire clé/valeur d'une étiquette.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Clé de l'étiquette. |
| value | java.lang.String |  |