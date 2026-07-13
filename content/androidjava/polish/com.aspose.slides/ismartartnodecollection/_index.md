---
title: ISmartArtNodeCollection
second_title: Aspose.Slides dla Androida poprzez odniesienie do Java API
description: Reprezentuje kolekcję węzłów SmartArt.
type: docs
url: /pl/com.aspose.slides/ismartartnodecollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Reprezentuje kolekcję węzłów SmartArt.

## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca węzeł według indeksu. |
| [addNode()](#addNode--) | Dodaje nowy węzeł lub podwęzeł. |
| [removeNode(int index)](#removeNode-int-) | Usuwa węzeł lub podwęzeł według indeksu. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Usuwa węzeł lub podwęzeł. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Dodaje nowy węzeł w wybranej pozycji kolekcji węzłów. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Zwraca węzeł według indeksu. Tylko do odczytu [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu zaczynający się od zera. |

**Zwraca:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)

### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Dodaje nowy węzeł lub podwęzeł.

**Zwraca:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Dodany węzeł

### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Usuwa węzeł lub podwęzeł według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks węzła zaczynający się od zera. |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Usuwa węzeł lub podwęzeł.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Węzeł do usunięcia. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Dodaje nowy węzeł w wybranej pozycji kolekcji węzłów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | int | Pozycja węzła zaczynająca się od zera. |

**Zwraca:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Dodany węzeł