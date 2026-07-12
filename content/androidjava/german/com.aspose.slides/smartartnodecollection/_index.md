---
title: SmartArtNodeCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von SmartArt-Knoten dar.
type: docs
url: /de/com.aspose.slides/smartartnodecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Stellt eine Sammlung von SmartArt-Knoten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt den Knoten nach Index zurück |
| [size()](#size--) | Gibt die Anzahl der Knoten in der Sammlung zurück Nur lesbar  int  Nur lesbar  int . |
| [addNode()](#addNode--) | Fügt einen neuen SmartArt-Knoten oder Unterknoten hinzu. |
| [removeNode(int index)](#removeNode-int-) | Entfernt Knoten oder Unterknoten nach Index |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Entfernt Knoten oder Unterknoten |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Fügt einen neuen Knoten an der ausgewählten Position der Knotensammlung hinzu |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der anzeigt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisations-Root zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Gibt den Knoten nach Index zurück

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des Elements |

**Rückgabewert:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Der SmartArt-Knoten
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Knoten in der Sammlung zurück Nur lesbar  int  Nur lesbar  int .

**Rückgabewert:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Fügt einen neuen SmartArt-Knoten oder Unterknoten hinzu.

**Rückgabewert:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hinzugefügter Knoten
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Entfernt Knoten oder Unterknoten nach Index

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index des Knotens |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Entfernt Knoten oder Unterknoten

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Zu entfernender Knoten |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Fügt einen neuen Knoten an der ausgewählten Position der Knotensammlung hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | int | Nullbasierte Knotenposition |

**Rückgabewert:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Hinzugefügter Knoten
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Gibt einen java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray. |
| index | int | Startindex im Zielarray. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der anzeigt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur lesbar  boolean .

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisations-Root zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object