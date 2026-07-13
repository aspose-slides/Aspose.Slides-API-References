---
title: BehaviorCollection
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Představuje kolekci efektů chování.
type: docs
url: /cs/com.aspose.slides/behaviorcollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Představuje kolekci efektů chování.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet chování v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu, která určuje, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze ke čtení. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Přidá nové chování do kolekce. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Určuje index konkrétní položky v seznamu. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Vloží nové chování do kolekce na zadaném indexu. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Odebere specifikované chování z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odebere chování z kolekce na zadaném indexu. |
| [clear()](#clear--) | Odebere všechna chování z kolekce. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [get_Item(int index)](#get-Item-int-) | Vrací chování na zadaném indexu. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Nastaví chování na zadaném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který iteruje přes kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### getCount() {#getCount--}
```
public final int getCount()
```

Vrací počet chování v kolekci. int pouze ke čtení.

**Vrací:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu, která určuje, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze ke čtení. boolean pouze ke čtení.

**Vrací:**
boolean - true pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze ke čtení; jinak false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Přidá nové chování do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování k přidání. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Určuje index konkrétní položky v seznamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt k vyhledání v seznamu. |

**Vrací:**
int - Index položky, pokud je nalezena v seznamu; jinak -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Vloží nové chování do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index, kam má být nové chování vloženo. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování k vložení. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Jednorozměrné pole, které je cílem pro prvky zkopírované z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít indexování od nuly. |
| arrayIndex | int | Nulový index v poli, odkud začíná kopírování. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Odebere specifikované chování z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Chování k odebrání. |

**Vrací:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odebere chování z kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má odebrat. |
### clear() {#clear--}
```
public final void clear()
```

Odebere všechna chování z kolekce.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt k vyhledání v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Vrací chování na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování k vrácení. |

**Vrací:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animace chování.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Nastaví chování na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které má být nastaveno. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Vrací enumerátor, který iteruje přes kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - java.util.Iterator pro celou kolekci.