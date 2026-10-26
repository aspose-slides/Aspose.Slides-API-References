---
title: IChartWall
second_title: Aspose.Slides voor Android via Java API Reference
description: Stelt wanden voor op 3D-diagrammen.
type: docs
url: /nl/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Stelt wanden voor op 3D-diagrammen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getThickness()](#getThickness--) | Geeft de wanddikte terug of stelt deze in als een percentage van de grootste dimensie van het plotvolume. |
| [setThickness(int value)](#setThickness-int-) | Geeft de wanddikte terug of stelt deze in als een percentage van de grootste dimensie van het plotvolume. |
| [getFormat()](#getFormat--) | Geeft de wandvulling, lijn, effect, 3D-stijlen terug. |
| [getPictureType()](#getPictureType--) | Geeft het picture type terug of stelt het in. |
| [setPictureType(int value)](#setPictureType-int-) | Geeft het picture type terug of stelt het in. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Geeft de wanddikte terug of stelt deze in als een percentage van de grootste dimensie van het plotvolume. Lezen/schrijven int.

**Retour:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Geeft de wanddikte terug of stelt deze in als een percentage van de grootste dimensie van het plotvolume. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Geeft de wandvulling, lijn, effect, 3D-stijlen terug. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Geeft het picture type terug of stelt het in. Lezen/schrijven [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Retour:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Geeft het picture type terug of stelt het in. Lezen/schrijven [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |