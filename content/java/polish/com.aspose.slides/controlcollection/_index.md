---
title: ControlCollection
second_title: Aspose.Slides dla Java – dokumentacja API
description: Zbiór kontrolek ActiveX.
type: docs
url: /pl/com.aspose.slides/controlcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Kolekcja kontrolek ActiveX.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę obiektów w kolekcji. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Tworzy i dodaje nową kontrolkę do kolekcji. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Usuwa kontrolkę ActiveX z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa kontrolkę ActiveX przechowywaną na określonej pozycji z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie kontrolki z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca kontrolkę na określonej pozycji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Javy dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje całą kolekcję do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość określającą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę obiektów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Tworzy i dodaje nową kontrolkę do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| controlType | int | Typ kontrolki do dodania. |
| x | float | Współrzędna X lewej krawędzi ramki kształtu. |
| y | float | Współrzędna Y górnej krawędzi ramki kształtu. |
| width | float | Szerokość ramki kształtu. |
| height | float | Wysokość ramki kształtu. |

**Zwraca:**
[IControl](../../com.aspose.slides/icontrol) - Utworzona kontrolka.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Usuwa kontrolkę ActiveX z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kontrolka do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa kontrolkę ActiveX przechowywaną na określonej pozycji z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kontrolki do usunięcia. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie kontrolki z kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Zwraca kontrolkę na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kontrolki. |

**Zwraca:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - IGenericEnumerator, który można użyć do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Zwraca iterator Javy dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje całą kolekcję do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa |
| index | int | Indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość określającą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject