---
title: IChartWall
second_title: Aspose.Slides for Java API Referencia
description: 3D diagramok falait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

A 3D diagramok falait reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getThickness()](#getThickness--) | Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékaként. |
| [setThickness(int value)](#setThickness-int-) | Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékaként. |
| [getFormat()](#getFormat--) | Visszaadja a fal kitöltését, vonalát, effektjét, 3D stílusait. |
| [getPictureType()](#getPictureType--) | Visszaadja vagy beállítja a képtípust. |
| [setPictureType(int value)](#setPictureType-int-) | Visszaadja vagy beállítja a képtípust. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékaként. Olvasás/írás int.

**Visszatérési érték:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékaként. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a fal kitöltését, vonalát, effektjét, 3D stílusait. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Visszaadja vagy beállítja a képtípust. Olvasás/írás [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Visszatérési érték:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Visszaadja vagy beállítja a képtípust. Olvasás/írás [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |