---
title: IMarker
second_title: Aspose.Slides for Android via Java API Reference
description: Represents marker of a chert.
type: docs
url: /hu/com.aspose.slides/imarker/
---```
public interface IMarker
```

A diagram jelölőjét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSymbol()](#getSymbol--) | A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [setSymbol(int value)](#setSymbol-int-) | A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [getFormat()](#getFormat--) | A jelölő kitöltését lekéri. |
| [getSize()](#getSize--) | A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
| [setSize(int value)](#setSize-int-) | A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Visszatér:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

A jelölő stílusát egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A jelölő kitöltését lekéri. Csak olvasás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás int.

**Visszatér:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

A jelölő méretét egy vonaldiagramon, szórt diagramon vagy radar diagramon képviseli. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |