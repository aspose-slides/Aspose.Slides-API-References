---
title: IBehaviorCollection
second_title: Aspose.Slides pro Android přes Java API Referenci
description: Představuje kolekci efektů chování.
type: docs
url: /cs/com.aspose.slides/ibehaviorcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Představuje kolekci efektů chování.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrátí chování na zadaném indexu. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Vrátí chování na zadaném indexu. |
| [getCount()](#getCount--) | Vrátí počet chování v kolekci. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Přidá nové chování do kolekce. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Určuje index konkrétní položky v seznamu. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Vloží nové chování do kolekce na zadaném indexu. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Odstraní specifikované chování z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní chování z kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechna chování z kolekce. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Vrátí chování na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má vrátit. |

**Návratová hodnota:**
[IBehavior](../../com.aspose.slides/ibehavior) - animace chování.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Vrátí chování na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má vrátit. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrátí počet chování v kolekci. Pouze pro čtení int.

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

Určuje index konkrétní položky v seznamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt, který se má najít v seznamu. |

**Návratová hodnota:**
int – Index položky, pokud je v seznamu nalezena; jinak -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Vloží nové chování do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index, kde má být nové chování vloženo. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování k vložení. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Odstraní specifikované chování z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování k odebrání. |

**Návratová hodnota:**
boolean – true, pokud bylo chování úspěšně odebráno, boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní chování z kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má odebrat. |
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
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt, který se má najít v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Návratová hodnota:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.