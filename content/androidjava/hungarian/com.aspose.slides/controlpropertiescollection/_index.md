---
title: ControlPropertiesCollection
second_title: Aspose.Slides Androidra vonatkozó Java API hivatkozás
description: AcitveX tulajdonságok egy gyűjteménye.
type: docs
url: /hu/com.aspose.slides/controlpropertiescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Az AcitveX tulajdonságok egy gyűjteménye.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Hozzáad egy tulajdonságot a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | Eltávolít egy megadott nevű tulajdonságot. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaadja vagy beállítja a tulajdonságot. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Visszaadja vagy beállítja a tulajdonságot. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Visszaadja a tulajdonságnevek gyűjteményét. |
| [clear()](#clear--) | Eltávolítja az összes tulajdonságot. |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben lévő tulajdonságok számát. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Hozzáad egy tulajdonságot a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String | A tulajdonság értéke. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Eltávolít egy megadott nevű tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A eltávolítandó tulajdonság neve. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Visszaadja vagy beállítja a tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |

**Visszatér:**
java.lang.String - Tulajdonság.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Visszaadja vagy beállítja a tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Visszaadja a tulajdonságnevek gyűjteményét. Csak olvasható [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Visszatér:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes tulajdonságot.

### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a gyűjteményben lévő tulajdonságok számát. Csak olvasható int.

**Visszatér:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Egy java.util.Iterator az egész gyűjteményhez.