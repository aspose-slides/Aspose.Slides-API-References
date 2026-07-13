---
title: IControlPropertiesCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Een collectie van ActiveX-besturingselementen.
type: docs
url: /nl/com.aspose.slides/icontrolpropertiescollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Een collectie van ActiveX-besturingselementen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Retourneert een aantal eigenschappen in de collectie. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Voegt een eigenschap toe aan de collectie. |
| [remove(String name)](#remove-java.lang.String-) | Verwijdert een eigenschap met de opgegeven naam. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retourneert of stelt eigenschap in. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retourneert of stelt eigenschap in. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Retourneert een aantal eigenschappen in de collectie. |
| [clear()](#clear--) | Verwijdert alle eigenschappen. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Retourneert een aantal eigenschappen in de collectie. Alleen-lezen int.

**Retour:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Voegt een eigenschap toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de eigenschap. |
| value | java.lang.String | De waarde van de eigenschap. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Verwijdert een eigenschap met de opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de te verwijderen eigenschap. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

Retourneert of stelt eigenschap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de eigenschap. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Retourneert een aantal eigenschappen in de collectie. Alleen-lezen [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Retour:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle eigenschappen.