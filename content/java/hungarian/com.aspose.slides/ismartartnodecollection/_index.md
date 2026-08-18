---
title: ISmartArtNodeCollection
second_title: Aspose.Slides Java API referencia
description: SmartArt csomópontok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ismartartnodecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

A SmartArt csomópontok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a csomópontot az index alapján. |
| [addNode()](#addNode--) | Új csomópontot vagy alcsomópontot ad hozzá. |
| [removeNode(int index)](#removeNode-int-) | Eltávolítja a csomópontot vagy alcsomópontot index alapján. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Eltávolítja a csomópontot vagy alcsomópontot. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Új csomópont hozzáadása a csomópontok gyűjteményének kiválasztott pozíciójába. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Visszaadja a csomópontot az index alapján. Csak olvasható [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem 0-alapú indexe. |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Új csomópont vagy alcsomópont hozzáadása.

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Csomópont vagy alcsomópont eltávolítása index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A csomópont 0-alapú indexe. |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Csomópont vagy alcsomópont eltávolítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Eltávolítandó csomópont. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Új csomópont hozzáadása a csomópontok gyűjteményének kiválasztott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | int | A csomópont 0-alapú pozíciója. |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont