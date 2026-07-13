---
title: ControlPropertiesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: En samling av AcitveX-egenskaper.
type: docs
url: /sv/com.aspose.slides/controlpropertiescollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

En samling av AcitveX-egenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Lägger till en egenskap i samlingen. |
| [remove(String name)](#remove-java.lang.String-) | Tar bort en egenskap med det angivna namnet. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller ställer in egenskapen. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returnerar eller ställer in egenskapen. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returnerar samlingen av egenskapsnamn. |
| [clear()](#clear--) | Tar bort alla egenskaper. |
| [getCount()](#getCount--) | Returnerar antalet egenskaper i samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Lägger till en egenskap i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på egenskapen. |
| value | java.lang.String | Värdet på egenskapen. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Tar bort en egenskap med det angivna namnet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på egenskapen som ska tas bort. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Returnerar eller ställer in egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på egenskapen. |

**Returnerar:**
java.lang.String - Egenskap.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Returnerar eller ställer in egenskapen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på egenskapen. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Returnerar samlingen av egenskapsnamn. Läs-endast [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returnerar:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla egenskaper.

### getCount() {#getCount--}
```
public final int getCount()
```

Returnerar antalet egenskaper i samlingen. Läs-endast int.

**Returnerar:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - En java.util.Iterator för hela samlingen.