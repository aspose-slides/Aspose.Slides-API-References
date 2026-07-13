---
title: ISequenceCollection
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Reprezentuje kolekci interaktivních sekvencí.
type: docs
url: /cs/com.aspose.slides/isequencecollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Reprezentuje kolekci interaktivních sekvencí.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci. Pouze ke čtení int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Přidá novou interaktivní sekvenci. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Odstraní zadanou sekvenci z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní sekvenci na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny sekvence z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Vrací sekvenci na zadaném indexu. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet prvků v kolekci. Pouze ke čtení int.

**Vrací:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Přidá novou interaktivní sekvenci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | objekt Shape [IShape](../../com.aspose.slides/ishape) |

**Vrací:**
[ISequence](../../com.aspose.slides/isequence) - Nová sekvence [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Odstraní zadanou sekvenci z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sekvence k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní sekvenci na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index elementu v kolekci int |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny sekvence z kolekce.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Vrací sekvenci na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index elementu. |

**Vrací:**
[ISequence](../../com.aspose.slides/isequence) - Objekt [ISequence](../../com.aspose.slides/isequence).