---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: Stelt muren op 3d-diagrammen voor.
type: docs
url: /nl/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Stelt muren op 3d-diagrammen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getThickness()](#getThickness--) | Geeft de wanddikte terug of stelt deze in als een percentage van de grootste afmeting van het plotvolume. |
| [setThickness(int value)](#setThickness-int-) | Geeft de wanddikte terug of stelt deze in als een percentage van de grootste afmeting van het plotvolume. |
| [getFormat()](#getFormat--) | Geeft de wandvulling, lijn, effect en 3d-stijlen terug. |
| [getPictureType()](#getPictureType--) | Geeft het afbeeldingstype terug of stelt het in. |
| [setPictureType(int value)](#setPictureType-int-) | Geeft het afbeeldingstype terug of stelt het in. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Geeft de wanddikte terug of stelt deze in als een percentage van de grootste afmeting van het plotvolume. Read/write int.

**Returns:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Geeft de wanddikte terug of stelt deze in als een percentage van de grootste afmeting van het plotvolume. Read/write int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Geeft de wandvulling, lijn, effect en 3d-stijlen terug. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Geeft het afbeeldingstype terug of stelt het in. Read/write [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Returns:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Geeft het afbeeldingstype terug of stelt het in. Read/write [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |