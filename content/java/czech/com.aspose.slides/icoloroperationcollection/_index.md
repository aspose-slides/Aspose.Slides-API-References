---
title: IColorOperationCollection
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje kolekci operací transformace barev.
type: docs
url: /cs/com.aspose.slides/icoloroperationcollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Reprezentuje kolekci operací transformace barev.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns or sets the operation at the specified index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returns or sets the operation at the specified index. |
| [add(int operation, float parameter)](#add-int-float-) | Adds a new operation to the end of collection. |
| [add(int operation)](#add-int-) | Adds a new operation to the end of collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserts the new operation to a collection. |
| [insert(int position, int operation)](#insert-int-int-) | Inserts the new operation to a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the color operation from a collection. |
| [clear()](#clear--) | Removes all color operations. |
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


Odstraní operaci barvy z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index operace barvy, která má být odstraněna. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny operace barvy.