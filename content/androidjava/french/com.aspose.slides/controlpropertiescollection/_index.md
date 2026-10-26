---
title: ControlPropertiesCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Une collection de propriétés AcitveX.
type: docs
url: /fr/com.aspose.slides/controlpropertiescollection/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Une collection de propriétés AcitveX.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Ajoute une propriété à la collection. |
| [remove(String name)](#remove-java.lang.String-) | Supprime une propriété avec le nom spécifié. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit la propriété. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Renvoie ou définit la propriété. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Renvoie la collection des noms de propriétés. |
| [clear()](#clear--) | Supprime toutes les propriétés. |
| [getCount()](#getCount--) | Renvoie le nombre de propriétés dans la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Ajoute une propriété à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de la propriété. |
| value | java.lang.String | La valeur de la propriété. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Supprime une propriété avec le nom spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom de la propriété à supprimer. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
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
public final void set_Item(String name, String value)
```

Renvoie ou définit la propriété.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Renvoie la collection des noms de propriétés. Lecture seule [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Renvoie :**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les propriétés.

### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre de propriétés dans la collection. Lecture seule int.

**Renvoie :**
int

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