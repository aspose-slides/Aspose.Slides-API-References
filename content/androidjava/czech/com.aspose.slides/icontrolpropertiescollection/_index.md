---
title: IControlPropertiesCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Kolekce ActiveX ovládacích prvků.
type: docs
url: /cs/com.aspose.slides/icontrolpropertiescollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Kolekce ovládacích prvků ActiveX.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet vlastností v kolekci. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Přidá vlastnost do kolekce. |
| [remove(String name)](#remove-java.lang.String-) | Odstraní vlastnost se zadaným názvem. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje vlastnost. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Vrací nebo nastavuje vlastnost. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Vrací počet vlastností v kolekci. |
| [clear()](#clear--) | Odstraní všechny vlastnosti. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet vlastností v kolekci. Pouze pro čtení int.

**Vrací:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Přidá vlastnost do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti. |
| value | java.lang.String | Hodnota vlastnosti. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Odstraní vlastnost se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti, která se má odstranit. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Vrací nebo nastavuje vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti. |

**Vrací:**
java.lang.String - Vlastnost.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Vrací nebo nastavuje vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Vrací počet vlastností v kolekci. Pouze pro čtení [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Vrací:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny vlastnosti.