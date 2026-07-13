---
title: ISmartArtNodeCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av SmartArt-noder.
type: docs
url: /sv/com.aspose.slides/ismartartnodecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Representerar en samling av SmartArt-noder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar noden med index. |
| [addNode()](#addNode--) | Lägger till ny nod eller undernod. |
| [removeNode(int index)](#removeNode-int-) | Tar bort nod eller undernod efter index. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Tar bort nod eller undernod. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Lägger till ny nod på den valda positionen i nodsamlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Returnerar noden med index. Skrivskyddad [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet. |

**Returnerar:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Lägger till ny nod eller undernod.

**Returnerar:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Tillagd nod
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Tar bort nod eller undernod efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för noden. |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Tar bort nod eller undernod.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nod att ta bort. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Lägger till ny nod på den valda positionen i nodsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Nollbaserad nodposition. |

**Returnerar:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Tillagd nod