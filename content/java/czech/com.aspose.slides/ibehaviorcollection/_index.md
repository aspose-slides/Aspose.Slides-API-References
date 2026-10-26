---
title: IBehaviorCollection
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje kolekci efektů chování.
type: docs
url: /cs/com.aspose.slides/ibehaviorcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Reprezentuje kolekci efektů chování.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací chování na zadaném indexu. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Vrací chování na zadaném indexu. |
| [getCount()](#getCount--) | Vrací počet chování v kolekci. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Přidá nové chování do kolekce. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Určuje index konkrétní položky v Listu. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Vloží nové chování do kolekce na zadaném indexu. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Odstraní zadané chování z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní chování z kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechna chování z kolekce. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```


Vrací chování na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má vrátit. |

**Návratová hodnota:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animace chování.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```


Vrací chování na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má vrátit. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Vrací počet chování v kolekci. Pouze pro čtení int.

**Návratová hodnota:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```


Přidá nové chování do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování, které se má přidat. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```


Určuje index konkrétní položky v Listu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt, který se má v Listu vyhledat. |

**Návratová hodnota:**
int - Index položky, pokud je nalezena v seznamu; jinak -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```


Vloží nové chování do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index, kam se má nové chování vložit. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování, které se má vložit. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```


Odstraní zadané chování z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování, které se má odstranit. |

**Návratová hodnota:**
boolean - True pokud bylo chování úspěšně odstraněno
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní chování z kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má odstranit. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechna chování z kolekce.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```


Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt, který se má vyhledat v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Návratová hodnota:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.