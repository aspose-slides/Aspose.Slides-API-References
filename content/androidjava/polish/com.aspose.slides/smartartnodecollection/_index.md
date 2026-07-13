---
title: SmartArtNodeCollection
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje kolekcję węzłów SmartArt.
type: docs
url: /pl/com.aspose.slides/smartartnodecollection/
---
**Dziedziczenie:**  
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)  
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Reprezentuje kolekcję węzłów SmartArt.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca węzeł według indeksu |
| [size()](#size--) | Zwraca liczbę węzłów w kolekcji Tylko do odczytu int Tylko do odczytu int . |
| [addNode()](#addNode--) | Dodaj nowy węzeł SmartArt lub podwęzeł. |
| [removeNode(int index)](#removeNode-int-) | Usuń węzeł lub podwęzeł według indeksu |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Usuń węzeł lub podwęzeł |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Dodaj nowy węzeł w wybranej pozycji kolekcji węzłów |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Zwraca węzeł według indeksu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu liczony od zera |

**Zwraca:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Węzeł SmartArt
### size() {#size--}
```
public final int size()
```

Zwraca liczbę węzłów w kolekcji Tylko do odczytu int Tylko do odczytu int .

**Zwraca:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Dodaj nowy węzeł SmartArt lub podwęzeł.

**Zwraca:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Dodany węzeł
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Usuń węzeł lub podwęzeł według indeksu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks węzła liczony od zera |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Usuń węzeł lub podwęzeł

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Węzeł do usunięcia |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Dodaj nowy węzeł w wybranej pozycji kolekcji węzłów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | int | Pozycja węzła liczona od zera |

**Zwraca:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Dodany węzeł
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean .

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object