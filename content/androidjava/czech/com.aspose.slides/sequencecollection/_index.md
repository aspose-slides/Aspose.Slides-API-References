---
title: SequenceCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje kolekci interaktivních sekvencí.
type: docs
url: /cs/com.aspose.slides/sequencecollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Reprezentuje kolekci interaktivních sekvencí.
## Metody

| Metoda | Popis |
| --- | --- |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci Pouze ke čtení int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Přidá novou interaktivní sekvenci. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Odstraní zadanou sekvenci ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní sekvenci na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny sekvence ze sbírky. |
| [get_Item(int index)](#get-Item-int-) | Vrací sekvenci na zadaném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který iteruje skrz sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet prvků v kolekci Pouze ke čtení int.

**Vrací:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Přidá novou interaktivní sekvenci. Čtení/zápis [Sequence](../../com.aspose.slides/sequence).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Vrací:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Odstraní zadanou sekvenci ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sekvence k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní sekvenci na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index sekvence, která má být smazána. |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny sekvence ze sbírky.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Vrací sekvenci na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[ISequence](../../com.aspose.slides/isequence) - Objekt [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Vrací enumerátor, který iteruje skrz sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - IGenericEnumerator, který lze použít k iteraci skrz sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - java.util.Iterator pro celou sbírku.