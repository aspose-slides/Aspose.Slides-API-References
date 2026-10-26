---
title: ColorOperationCollection
second_title: Aspose.Slides pro Android přes referenci Java API
description: Representuje kolekci operací transformace barev.
type: docs
url: /cs/com.aspose.slides/coloroperationcollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Representuje kolekci operací transformace barev.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet operací v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací nebo nastaví operaci na zadaném indexu. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Vrací nebo nastaví operaci na zadaném indexu. |
| [add(int operation, float parameter)](#add-int-float-) | Přidá novou operaci na konec kolekce. |
| [add(int operation)](#add-int-) | Přidá novou operaci na konec kolekce. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Vloží novou operaci do kolekce. |
| [insert(int position, int operation)](#insert-int-int-) | Vloží novou operaci do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní operaci barvy z kolekce. |
| [clear()](#clear--) | Odstraní všechny operace barvy. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu, která udává, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [deepClone()](#deepClone--) | Vytvoří kopii kolekce ColorOperationCollection. |
| [cloneT()](#cloneT--) | Klonuje aktuální objekt |
### size() {#size--}
```
public final int size()
```

Vrací počet operací v kolekci. Pouze ke čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Vrací nebo nastaví operaci na zadaném indexu. Čtení a zápis [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Vrací nebo nastaví operaci na zadaném indexu. Čtení a zápis [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
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
public final IColorOperation add(int operation)
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
public final IColorOperation insert(int position, int operation, float parameter)
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
public final IColorOperation insert(int position, int operation)
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
public final void removeAt(int index)
```

Odstraní operaci barvy z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index operace barvy, která má být odstraněna. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny operace barvy.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - IGenericEnumerator, který lze použít pro iteraci kolekce.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která udává, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Vytvoří kopii kolekce ColorOperationCollection.

**Vrací:**
java.lang.Object - Nová [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) kolekce.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Klonuje aktuální objekt

**Vrací:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Klon