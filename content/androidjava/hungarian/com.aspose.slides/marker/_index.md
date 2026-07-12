---
title: Marker
second_title: Aspose.Slides Androidhoz a Java API Referencián keresztül
description: Képviseli egy diagram jelölőjét.
type: docs
url: /hu/com.aspose.slides/marker/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IMarker](../../com.aspose.slides/imarker), com.aspose.slides.IDOMObject
```
public class Marker implements IMarker, IDOMObject
```

A jelölőt egy diagramon képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSymbol()](#getSymbol--) | A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [setSymbol(int value)](#setSymbol-int-) | A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [getFormat()](#getFormat--) | A jelölő kitöltését lekéri vagy beállítja. |
| [getSize()](#getSize--) | A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [setSize(int value)](#setSize-int-) | A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSymbol() {#getSymbol--}
```
public final int getSymbol()
```

A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Visszatér:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public final void setSymbol(int value)
```

A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A jelölő kitöltését lekéri vagy beállítja. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public final int getSize()
```

A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás int.

**Visszatér:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```

A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject