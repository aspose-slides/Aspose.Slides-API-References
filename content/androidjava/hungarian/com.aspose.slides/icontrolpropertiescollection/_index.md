---
title: IControlPropertiesCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: ActiveX vezérlők gyűjteménye.
type: docs
url: /hu/com.aspose.slides/icontrolpropertiescollection/
---
**Az összes megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX vezérlők gyűjteménye.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben lévő tulajdonságok számát. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Tulajdonságot ad a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | Eltávolít egy megadott névű tulajdonságot. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaad vagy beállítja a tulajdonságot. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Visszaad vagy beállítja a tulajdonságot. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Visszaadja a gyűjteményben lévő tulajdonságok számát. |
| [clear()](#clear--) | Eltávolítja az összes tulajdonságot. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Visszaadja a gyűjteményben lévő tulajdonságok számát. Csak olvasható int.

**Visszatér:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Tulajdonságot ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String | A tulajdonság értéke. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Eltávolít egy megadott névű tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az eltávolítandó tulajdonság neve. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Visszaad vagy beállítja a tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |

**Visszatér:**
java.lang.String - Tulajdonság.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Visszaad vagy beállítja a tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Visszaadja a gyűjteményben lévő tulajdonságok számát. Csak olvasható [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Visszatér:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes tulajdonságot.