---
title: ControlPropertiesCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Een verzameling van AcitveX-eigenschappen.
type: docs
url: /nl/com.aspose.slides/controlpropertiescollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Een verzameling van AcitveX-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Voegt een eigenschap toe aan de verzameling. |
| [remove(String name)](#remove-java.lang.String-) | Verwijdert een eigenschap met de opgegeven naam. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Geeft een eigenschap terug of stelt deze in. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Geeft een eigenschap terug of stelt deze in. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Geeft de verzameling van eigenschapsnamen terug. |
| [clear()](#clear--) | Verwijdert alle eigenschapen. |
| [getCount()](#getCount--) | Geeft een aantal eigenschapen in de verzameling terug. |
| [iterator()](#iterator--) | Geeft een enumerator terug die door de verzameling iterereert. |
| [iteratorJava()](#iteratorJava--) | Geeft een java-iterator terug voor de volledige verzameling. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Voegt een eigenschap toe aan de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de eigenschap. |
| value | java.lang.String | De waarde van de eigenschap. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Verwijdert een eigenschap met de opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de eigenschap die verwijderd moet worden. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Geeft een eigenschap terug of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de eigenschap. |

**Returns:**
java.lang.String - Eigenschap.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Geeft een eigenschap terug of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de eigenschap. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Geeft de verzameling van eigenschapsnamen terug. Alleen-lezen [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returns:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle eigenschapen.

### getCount() {#getCount--}
```
public final int getCount()
```


Geeft een aantal eigenschapen in de verzameling terug. Alleen-lezen int.

**Returns:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Geeft een enumerator terug die door de verzameling iterereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Geeft een java-iterator terug voor de volledige verzameling.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Een java.util.Iterator voor de volledige collectie.