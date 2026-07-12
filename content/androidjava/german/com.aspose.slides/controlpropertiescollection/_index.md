---
title: ControlPropertiesCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Eine Sammlung von AcitveX-Eigenschaften.
type: docs
url: /de/com.aspose.slides/controlpropertiescollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Eine Sammlung von AcitveX-Eigenschaften.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Fügt der Sammlung eine Eigenschaft hinzu. |
| [remove(String name)](#remove-java.lang.String-) | Entfernt eine Eigenschaft mit dem angegebenen Namen. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt die Eigenschaft zurück oder legt sie fest. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Gibt die Eigenschaft zurück oder legt sie fest. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Gibt die Sammlung von Eigenschaftsnamen zurück. |
| [clear()](#clear--) | Entfernt alle Eigenschaften. |
| [getCount()](#getCount--) | Gibt die Anzahl der Eigenschaften in der Sammlung zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Fügt der Sammlung eine Eigenschaft hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name der Eigenschaft. |
| value | java.lang.String | Der Wert der Eigenschaft. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Entfernt eine Eigenschaft mit dem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name der zu entfernenden Eigenschaft. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Gibt die Eigenschaft zurück oder legt sie fest.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der Eigenschaft. |

**Rückgabewert:**
java.lang.String - Eigenschaft.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Gibt die Eigenschaft zurück oder legt sie fest.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der Eigenschaft. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Gibt die Sammlung von Eigenschaftsnamen zurück. Nur lesend [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Rückgabewert:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Eigenschaften.

### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Eigenschaften in der Sammlung zurück. Nur lesend int.

**Rückgabewert:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Ein java.util.Iterator für die gesamte Sammlung.