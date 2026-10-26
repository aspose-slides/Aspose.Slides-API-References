---
title: PortionCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Representuje kolekci částí.
type: docs
url: /cs/com.aspose.slides/portioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Represents a collection of portions.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Získá počet prvků skutečně obsažených v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Získá prvek na zadaném indexu. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Přidá Portion na konec kolekce. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Určuje index konkrétní položky v Listu. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Vloží Portion do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. Pouze pro čtení boolean.

**Vrací:**
boolean - true pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení; jinak false.
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

Určuje index konkrétní položky v Listu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který se má v Listu najít. |

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
| index | int | Nulový index, na který má být Portion vložena. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, která má být vložena. |
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
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který se má v [IGenericCollection](../../com.aspose.slides/igenericcollection) najít. |

**Vrací:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Jednorozměrné pole, které je cílem kopiovaných prvků z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít nulové indexování. |
| arrayIndex | int | Nulový index v poli, od kterého začíná kopírování. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Odstraní první výskyt konkrétního objektu ze [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který má být odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud byla položka úspěšně odstraněna z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud položka není v originálním [IGenericCollection](../../com.aspose.slides/igenericcollection) nalezena.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - An java.util.Iterator for the entire collection.