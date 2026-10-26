---
title: PortionCollection
second_title: Aspose.Slides pro Java API Reference
description: Representuje kolekci částí.
type: docs
url: /cs/com.aspose.slides/portioncollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Representuje kolekci částí.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Získá počet prvků skutečně obsažených v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu, která udává, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Získá prvek na zadaném indexu. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Přidá Portion na konec kolekce. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Určuje index konkrétní položky v List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Vloží Portion do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |

### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet prvků skutečně obsažených v kolekci. int (pouze pro čtení).

**Vrací:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu, která udává, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. boolean (pouze pro čtení).

**Vrací:**
boolean - true, pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení; jinak false.

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Přidá Portion na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, který má být přidán na konec kolekce. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Určuje index konkrétní položky v List.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který má být v List nalezen. |

**Vrací:**
int - Index položky, pokud je v seznamu nalezena; jinak -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Vloží Portion do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index, na kterém má být Portion vložena. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, který se má vložit. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny prvky z kolekce.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který má být nalezen v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true, pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Jednorozměrné pole, které je cílem prvků zkopírovaných z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít nulové indexování. |
| arrayIndex | int | Nulově založený index v poli, od kterého začíná kopírování. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který má být odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true, pokud byla položka úspěšně odstraněna z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud položka nebyla nalezena v původním [IGenericCollection](../../com.aspose.slides/igenericcollection).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index prvku, který má být odstraněn. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Vrátí enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - java.util.Iterator pro celou kolekci.