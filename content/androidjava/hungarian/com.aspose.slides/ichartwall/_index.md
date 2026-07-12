---
title: IChartWall
second_title: Aspose.Slides Androidra Java API hivatkozással
description: Ábrázolja a falakat a 3D diagramokban.
type: docs
url: /hu/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Ábrázolja a falakat a 3D diagramokban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getThickness()](#getThickness--) | Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékában. |
| [setThickness(int value)](#setThickness-int-) | Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékában. |
| [getFormat()](#getFormat--) | Visszaadja a fal kitöltését, vonalát, effektusát, 3D stílusait. |
| [getPictureType()](#getPictureType--) | Visszaadja vagy beállítja a kép típusát. |
| [setPictureType(int value)](#setPictureType-int-) | Visszaadja vagy beállítja a kép típusát. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékában. Olvasás/írás int.

**Visszatérési érték:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Visszaadja vagy beállítja a falak vastagságát a diagram térfogatának legnagyobb dimenziójának százalékában. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a fal kitöltését, vonalát, effektusát, 3D stílusait. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Visszaadja vagy beállítja a kép típusát. Olvasás/írás [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Visszatérési érték:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Visszaadja vagy beállítja a kép típusát. Olvasás/írás [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |