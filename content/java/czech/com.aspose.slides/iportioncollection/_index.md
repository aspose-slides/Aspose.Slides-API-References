---
title: IPortionCollection
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje kolekci částí.
type: docs
url: /cs/com.aspose.slides/iportioncollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Representuje kolekci objektů typu Portion.

## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getCount()](#getCount--) | Získá počet prvků, které jsou ve skutečnosti obsaženy v kolekci. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Přidá objekt Portion na konec kolekce. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Určuje index konkrétního objektu Portion v kolekci. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Vloží objekt Portion do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet prvků, které jsou ve skutečnosti obsaženy v kolekci. Pouze pro čtení int.

**Vrací:**
int

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Přidá objekt Portion na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, který se má přidat na konec kolekce. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Určuje index konkrétního objektu Portion v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Portion, který se má v kolekci najít. |

**Vrací:**
int - Index položky, pokud je nalezena v kolekci; jinak -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Vloží objekt Portion do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má objekt Portion vložit. |
| value | [IPortion](../../com.aspose.slides/iportion) | Objekt Portion, který se má vložit. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky z kolekce.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který se má najít v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který se má odstranit z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud byl objekt úspěšně odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud objekt není nalezen v původním [IGenericCollection](../../com.aspose.slides/igenericcollection).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má odstranit. |