---
title: IControlPropertiesCollection
second_title: Aspose.Slides Java API referenciája
description: ActiveX vezérlők gyűjteménye.
type: docs
url: /hu/com.aspose.slides/icontrolpropertiescollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX vezérlők gyűjteménye.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | A gyűjteményben lévő tulajdonságok számát adja vissza. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Tulajdonságot ad hozzá a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | Eltávolít egy tulajdonságot a megadott névvel. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Tulajdonságot ad vissza vagy állít be. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Tulajdonságot ad vissza vagy állít be. |
| [getNamesOfProperties()](#getNamesOfProperties--) | A gyűjteményben lévő tulajdonságok számát adja vissza. |
| [clear()](#clear--) | Eltávolítja az összes tulajdonságot. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

A gyűjteményben lévő tulajdonságok számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Tulajdonságot ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String | A tulajdonság értéke. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Eltávolít egy tulajdonságot a megadott névvel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A törlendő tulajdonság neve. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Tulajdonságot ad vissza vagy állít be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |

**Visszatér:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Tulajdonságot ad vissza vagy állít be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A tulajdonság neve. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

A gyűjteményben lévő tulajdonságok számát adja vissza. Csak olvasható [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Visszatér:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes tulajdonságot.