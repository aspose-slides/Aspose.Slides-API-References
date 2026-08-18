---
title: IMarker
second_title: Aspose.Slides for Java API Reference
description: A chert jelölőjét képviseli.
type: docs
url: /hu/com.aspose.slides/imarker/
---```
public interface IMarker
```

A chert jelölőjét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSymbol()](#getSymbol--) | A jelölő stílusát képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. |
| [setSymbol(int value)](#setSymbol-int-) | A jelölő stílusát képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. |
| [getFormat()](#getFormat--) | A jelölő kitöltését adja vissza. |
| [getSize()](#getSize--) | A jelölő méretét képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. |
| [setSize(int value)](#setSize-int-) | A jelölő méretét képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

A jelölő stílusát képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. Olvasás/írás [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Visszatérési érték:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

A jelölő stílusát képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. Olvasás/írás [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A jelölő kitöltését adja vissza. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

A jelölő méretét képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. Olvasás/írás int.

**Visszatérési érték:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

A jelölő méretét képviseli vonaldiagramban, szórási diagramban vagy radar diagramon. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |