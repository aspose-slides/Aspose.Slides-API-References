---
title: ISmartArtNodeCollection
second_title: Aspose.Slides Android számára Java API-referencia
description: SmartArt csomópontok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ismartartnodecollection/
---
**Összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt csomópontok gyűjteményét képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a csomópontot index alapján. |
| [addNode()](#addNode--) | Új csomópontot vagy alcsomópontot ad hozzá. |
| [removeNode(int index)](#removeNode-int-) | Eltávolítja a csomópontot vagy alcsomópontot index alapján. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Eltávolítja a csomópontot vagy alcsomópontot. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Új csomópontot ad hozzá a csomópontok gyűjteményének kiválasztott pozíciójában. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Visszaadja a csomópontot index alapján. Csak olvasható [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A nulla-alapú index az elemhez. |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Új csomópontot vagy alcsomópontot ad hozzá.

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Eltávolítja a csomópontot vagy alcsomópontot index alapján.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Nulla-alapú index a csomóponthoz |
### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Eltávolítja a csomópontot vagy alcsomópontot.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Az eltávolítandó csomópont. |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Új csomópontot ad hozzá a csomópontok gyűjteményének kiválasztott pozíciójában.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Nulla-alapú csomópont pozíció. |

**Visszatérési érték:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hozzáadott csomópont