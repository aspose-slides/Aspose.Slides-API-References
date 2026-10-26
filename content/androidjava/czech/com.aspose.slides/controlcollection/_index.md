---
title: ControlCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Kolekce ovládacích prvků ActiveX.
type: docs
url: /cs/com.aspose.slides/controlcollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Kolekce ovládacích prvků ActiveX.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet objektů v kolekci. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Vytvoří a přidá nový ovládací prvek do kolekce. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Odstraní ovládací prvek ActiveX z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní ovládací prvek ActiveX uložený na zadané pozici z kolekce. |
| [clear()](#clear--) | Odstraní všechny ovládací prvky z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Vrací ovládací prvek na zadané pozici. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje celou kolekci do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Vrací počet objektů v kolekci. Pouze ke čtení int.

**Vrací:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


Vytvoří a přidá nový ovládací prvek do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| controlType | int | Typ ovládacího prvku, který se má přidat. |
| x | float | Souřadnice X levé strany rámce tvaru. |
| y | float | Souřadnice Y horní strany rámce tvaru. |
| width | float | Šířka rámce tvaru. |
| height | float | Výška rámce tvaru. |

**Vrací:**
[IControl](../../com.aspose.slides/icontrol) - Vytvořený ovládací prvek.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


Odstraní ovládací prvek ActiveX z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ovládací prvek k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní ovládací prvek ActiveX uložený na zadané pozici z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku, který se má odstranit. |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny ovládací prvky z kolekce.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


Vrací ovládací prvek na zadané pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovládacího prvku. |

**Vrací:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje celou kolekci do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole |
| index | int | Index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.