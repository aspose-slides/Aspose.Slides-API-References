---
title: ISmartArtNodeCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje kolekci uzlů SmartArt.
type: docs
url: /cs/com.aspose.slides/ismartartnodecollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Reprezentuje kolekci uzlů SmartArt.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací uzel podle indexu. |
| [addNode()](#addNode--) | Přidá nový uzel nebo poduzel. |
| [removeNode(int index)](#removeNode-int-) | Odstraní uzel nebo poduzel podle indexu. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Odstraní uzel nebo poduzel. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Přidá nový uzel na vybrané pozici kolekce uzlů. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Vrací uzel podle indexu. Pouze pro čtení [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku. |

**Vrací:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Přidá nový uzel nebo poduzel.

**Vrací:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Přidaný uzel
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Odstraní uzel nebo poduzel podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index uzlu. |
### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Odstraní uzel nebo poduzel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Uzel k odstranění. |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Přidá nový uzel na vybranou pozici kolekce uzlů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | int | Pozice uzlu počínající od nuly. |

**Vrací:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Přidaný uzel