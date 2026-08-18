---
title: ControlPropertiesCollection
second_title: Aspose.Slides Java API hivatkozás
description: Az ActiveX tulajdonságok gyűjteménye.
type: docs
url: /hu/com.aspose.slides/controlpropertiescollection/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Az ActiveX tulajdonságok gyűjteménye.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Tulajdonságot ad hozzá a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | Eltávolít egy tulajdonságot a megadott névvel. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaad vagy beállít egy tulajdonságot. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Visszaad vagy beállít egy tulajdonságot. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Visszaadja a tulajdonságnevek gyűjteményét. |
| [clear()](#clear--) | Eltávolítja az összes tulajdonságot. |
| [getCount()](#getCount--) | A gyűjteményben lévő tulajdonságok számát adja vissza. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Tulajdonságot ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String | A tulajdonság értéke. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Eltávolít egy tulajdonságot a megadott névvel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A eltávolítandó tulajdonság neve. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Visszaad vagy beállít egy tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |

**Visszatérési érték:**
java.lang.String - Tulajdonság.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Visszaad vagy beállít egy tulajdonságot.

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

**Visszatérési érték:**
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

A gyűjteményben lévő tulajdonságok számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Egy java.util.Iterator a teljes gyűjteményhez.