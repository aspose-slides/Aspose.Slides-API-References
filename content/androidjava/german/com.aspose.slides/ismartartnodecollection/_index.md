---
title: ISmartArtNodeCollection
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt eine Sammlung von SmartArt-Knoten dar.
type: docs
url: /de/com.aspose.slides/ismartartnodecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Stellt eine Sammlung von SmartArt-Knoten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Knoten nach Index zurück. |
| [addNode()](#addNode--) | Fügt einen neuen Knoten oder Unterknoten hinzu. |
| [removeNode(int index)](#removeNode-int-) | Entfernt Knoten oder Unterknoten nach Index. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Entfernt Knoten oder Unterknoten. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Fügt einen neuen Knoten an der ausgewählten Position in der Knotensammlung hinzu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Gibt den Knoten nach Index zurück. Nur lesbar [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des Elements. |

**Rückgabe:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Fügt einen neuen Knoten oder Unterknoten hinzu.

**Rückgabe:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hinzugefügter Knoten
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Entfernt Knoten oder Unterknoten nach Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index des Knotens |

### removeNode(com.aspose.slides.ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Entfernt Knoten oder Unterknoten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Zu entfernender Knoten. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Fügt einen neuen Knoten an der ausgewählten Position in der Knotensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | int | Nullbasierte Position des Knotens. |

**Rückgabe:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hinzugefügter Knoten