---
title: IControlPropertiesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: En samling av ActiveX-kontroller.
type: docs
url: /sv/com.aspose.slides/icontrolpropertiescollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

En samling av ActiveX-kontroller.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet egenskaper i samlingen. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Lägger till en egenskap i samlingen. |
| [remove(String name)](#remove-java.lang.String-) | Tar bort en egenskap med det angivna namnet. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller anger egenskap. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returnerar eller anger egenskap. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returnerar antalet egenskaper i samlingen. |
| [clear()](#clear--) | Tar bort alla egenskaper. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet egenskaper i samlingen. Skrivskyddad int.

**Returnerar:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Lägger till en egenskap i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Egenskapens namn. |
| value | java.lang.String | Värdet av egenskapen. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Tar bort en egenskap med det angivna namnet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på egenskapen som ska tas bort. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Returnerar eller anger egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Egenskapens namn. |

**Returnerar:**
java.lang.String - Egenskap.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Returnerar eller anger egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Egenskapens namn. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Returnerar antalet egenskaper i samlingen. Skrivskyddad [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returnerar:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla egenskaper.