---
title: BehaviorCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci efektů chování.
type: docs
url: /cs/com.aspose.slides/behaviorcollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Reprezentuje kolekci efektů chování.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet chování v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Přidá nové chování do kolekce. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Určuje index konkrétní položky v seznamu. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Vloží nové chování do kolekce na určeném indexu. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje určitým indexem pole. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Odstraní specifikované chování z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní chování z kolekce na určeném indexu. |
| [clear()](#clear--) | Odstraní všechna chování z kolekce. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [get_Item(int index)](#get-Item-int-) | Vrací chování na určeném indexu. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Nastaví chování na určeném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### getCount() {#getCount--}
```
public final int getCount()
```

Vrací počet chování v kolekci. Pouze pro čtení int.

**Vrací:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. Pouze pro čtení boolean.

**Vrací:**
boolean - true, pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení; jinak false.
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
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt, který se má najít v seznamu. |

**Vrací:**
int - Index položky, pokud je v seznamu nalezena; jinak -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Vloží nové chování do kolekce na určeném indexu.

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
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Jednorozměrné pole, které je cílem prvků zkopírovaných z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít indexování od nuly. |
| arrayIndex | int | Index v poli, od kterého začíná kopírování (základní index 0). |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Odstraní specifikované chování z kolekce.

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

Odstraní chování z kolekce na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má odstranit. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechna chování z kolekce.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objekt, který se má najít v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true, pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Vrací chování na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má vrátit. |

**Vrací:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animace chování.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Nastaví chování na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index chování, které se má nastavit. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - java.util.Iterator pro celou kolekci.