---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt Wände in 3D-Diagrammen dar.
type: docs
url: /de/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Stellt Wände in 3D-Diagrammen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThickness()](#getThickness--) | Gibt die Wandstärke zurück oder legt sie als Prozentsatz der größten Dimension des Plotvolumens fest. |
| [setThickness(int value)](#setThickness-int-) | Gibt die Wandstärke zurück oder legt sie als Prozentsatz der größten Dimension des Plotvolumens fest. |
| [getFormat()](#getFormat--) | Gibt die Wandfüllung, Linie, Effekt und 3D-Stile zurück. |
| [getPictureType()](#getPictureType--) | Gibt den Bildtyp zurück oder legt ihn fest. |
| [setPictureType(int value)](#setPictureType-int-) | Gibt den Bildtyp zurück oder legt ihn fest. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Gibt die Wandstärke zurück oder legt sie als Prozentsatz der größten Dimension des Plotvolumens fest. Lesen/Schreiben int.

**Rückgabewert:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Gibt die Wandstärke zurück oder legt sie als Prozentsatz der größten Dimension des Plotvolumens fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Gibt die Wandfüllung, Linie, Effekt und 3D-Stile zurück. Nur-Lesen [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Gibt den Bildtyp zurück oder legt ihn fest. Lesen/Schreiben [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Rückgabewert:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Gibt den Bildtyp zurück oder legt ihn fest. Lesen/Schreiben [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |