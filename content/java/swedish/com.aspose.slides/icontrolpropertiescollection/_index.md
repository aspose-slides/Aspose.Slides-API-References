---
title: IControlPropertiesCollection
second_title: Aspose.Slides för Java API-referens
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
| [getCount()](#getCount--) | Returnerar ett antal egenskaper i samlingen. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Lägger till en egenskap i samlingen. |
| [remove(String name)](#remove-java.lang.String-) | Tar bort en egenskap med det angivna namnet. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller ställer in egenskap. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returnerar eller ställer in egenskap. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returnerar ett antal egenskaper i samlingen. |
| [clear()](#clear--) | Tar bort alla egenskaper. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar ett antal egenskaper i samlingen. Skrivskyddad int.

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
| name | java.lang.String | Namnet på egenskapen. |
| value | java.lang.String | Värdet på egenskapen. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Tar bort en egenskap med det angivna namnet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på egenskapen att ta bort. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Returnerar eller ställer in egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Egenskapens namn. |

**Returnerar:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Returnerar eller ställer in egenskap.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Egenskapens namn. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Returnerar ett antal egenskaper i samlingen. Skrivskyddad [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returnerar:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla egenskaper.