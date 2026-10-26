---
title: ISequenceCollection
second_title: Aspose.Slides pro Java - referenční API
description: Representuje kolekci interaktivních sekvencí.
type: docs
url: /cs/com.aspose.slides/isequencecollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Representuje kolekci interaktivních sekvencí.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci. Pouze pro čtení int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Přidá novou interaktivní sekvenci. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Odstraní zadanou sekvenci z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní sekvenci na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny sekvence z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Vrací sekvenci na zadaném indexu. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet prvků v kolekci. Pouze pro čtení int.

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
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Objekt tvaru [IShape](../../com.aspose.slides/ishape) |

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
| index | int | Index prvku v kolekci int |

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
| index | int | Index prvku. |

**Vrací:**
[ISequence](../../com.aspose.slides/isequence) - The [ISequence](../../com.aspose.slides/isequence) objekt.