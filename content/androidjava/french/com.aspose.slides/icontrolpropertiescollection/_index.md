---
title: IControlPropertiesCollection
second_title: Référence API Aspose.Slides pour Android via Java
description: Une collection de contrôles ActiveX.
type: docs
url: /fr/com.aspose.slides/icontrolpropertiescollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Une collection de contrôles ActiveX.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Renvoie un nombre de propriétés dans la collection. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Ajoute une propriété à la collection. |
| [remove(String name)](#remove-java.lang.String-) | Supprime une propriété avec le nom spécifié. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit la propriété. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Renvoie ou définit la propriété. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Renvoie un nombre de propriétés dans la collection. |
| [clear()](#clear--) | Supprime toutes les propriétés. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Renvoie un nombre de propriétés dans la collection. Lecture seule int.

**Renvoie :**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Ajoute une propriété à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de la propriété. |
| value | java.lang.String | La valeur de la propriété. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Supprime une propriété avec le nom spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de la propriété à supprimer. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Renvoie ou définit la propriété.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété. |

**Renvoie :**
java.lang.String - Propriété.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Renvoie ou définit la propriété.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Renvoie un nombre de propriétés dans la collection. Lecture seule [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Renvoie :**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les propriétés.