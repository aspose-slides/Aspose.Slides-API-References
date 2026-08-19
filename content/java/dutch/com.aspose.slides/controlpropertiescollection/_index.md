---
title: ControlPropertiesCollection
second_title: Aspose.Slides voor Java API-referentie
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
| [get_Item(String name)](#get-Item-java.lang.String-) | Retourneert of stelt eigenschap in. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retourneert of stelt eigenschap in. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Retourneert de verzameling van eigenschapsnamen. |
| [clear()](#clear--) | Verwijdert alle eigenschappen. |
| [getCount()](#getCount--) | Retourneert het aantal eigenschappen in de verzameling. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige verzameling. |
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
| name | java.lang.String | De naam van de te verwijderen eigenschap. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Retourneert of stelt eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de eigenschap. |

**Retour:**
java.lang.String - Eigenschap.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Retourneert of stelt eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de eigenschap. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Retourneert de verzameling van eigenschapsnamen. Alleen-lezen [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Retour:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle eigenschappen.

### getCount() {#getCount--}
```
public final int getCount()
```

Retourneert het aantal eigenschappen in de verzameling. Alleen-lezen int.

**Retour:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Retourneert een enumerator die door de verzameling iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Retourneert een java-iterator voor de volledige verzameling.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Een java.util.Iterator voor de volledige verzameling.