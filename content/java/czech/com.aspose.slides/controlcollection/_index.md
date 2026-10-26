---
title: ControlCollection
second_title: Aspose.Slides pro Java API Reference
description: Sbírka ActiveX ovladačů.
type: docs
url: /cs/com.aspose.slides/controlcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Sbírka ActiveX ovladačů.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet objektů ve sbírce. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Vytvoří a přidá nový ovladač do sbírky. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Odstraní ActiveX ovladač ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní ActiveX ovladač uložený na zadané pozici ze sbírky. |
| [clear()](#clear--) | Odstraní všechny ovladače ze sbírky. |
| [get_Item(int index)](#get-Item-int-) | Vrací ovladač na určené pozici. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje celou sbírku do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke sbírce synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Vrací počet objektů ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


Vytvoří a přidá nový ovladač do sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| controlType | int | Typ ovladače k přidání. |
| x | float | Souřadnice X levé strany rámečku tvaru. |
| y | float | Souřadnice Y horní strany rámečku tvaru. |
| width | float | Šířka rámečku tvaru. |
| height | float | Výška rámečku tvaru. |

**Vrací:**
[IControl](../../com.aspose.slides/icontrol) - Vytvořený ovladač.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


Odstraní ActiveX ovladač ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ovladač k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní ActiveX ovladač uložený na zadané pozici ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovladače k odstranění. |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny ovladače ze sbírky.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


Vrací ovladač na určené pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index ovladače. |

**Vrací:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


Vrací enumerátor, který prochází sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator pro celou sbírku.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje celou sbírku do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole |
| index | int | Index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu označující, zda je přístup ke sbírce synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject