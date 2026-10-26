---
title: IColorOperationCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje kolekci operací transformace barev.
type: docs
url: /cs/com.aspose.slides/icoloroperationcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Představuje kolekci operací transformace barev.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací nebo nastavuje operaci na zadaném indexu. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Vrací nebo nastavuje operaci na zadaném indexu. |
| [add(int operation, float parameter)](#add-int-float-) | Přidá novou operaci na konec kolekce. |
| [add(int operation)](#add-int-) | Přidá novou operaci na konec kolekce. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Vloží novou operaci do kolekce. |
| [insert(int position, int operation)](#insert-int-int-) | Vloží novou operaci do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní operaci barvy ze sbírky. |
| [clear()](#clear--) | Odstraní všechny operace barvy. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Vrací nebo nastavuje operaci na zadaném indexu. Čtení/zápis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Vrací nebo nastavuje operaci na zadaném indexu. Čtení/zápis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Přidá novou operaci na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operation | int | Typ operace. |
| parameter | float | Parametr operace. |

**Vrací:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Přidaná operace.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```


Přidá novou operaci na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operation | int | Typ operace. |

**Vrací:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Přidaná operace.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```


Vloží novou operaci do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | int | Index, na který bude operace vložena. |
| operation | int | Typ operace. |
| parameter | float | Parametr operace. |

**Vrací:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Vložená operace.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```


Vloží novou operaci do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | int | Index, na který bude operace vložena. |
| operation | int | Typ operace. |

**Vrací:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Vložená operace.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní operaci barvy ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index operace barvy k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny operace barvy.