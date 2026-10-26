---
title: IPictureFrame
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Rahmen mit einem Bild darin dar.
type: docs
url: /de/com.aspose.slides/ipictureframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Stellt einen Rahmen mit einem Bild darin dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Gibt die Locks von PictureFrame zurück. |
| [getPictureFormat()](#getPictureFormat--) | Gibt das PictureFillFormat-Objekt für einen Bildrahmen zurück. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Gibt die Skalierung der Höhe (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Gibt die Skalierung der Höhe (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Gibt die Skalierung der Breite (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Gibt die Skalierung der Breite (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


Gibt die Locks von PictureFrame zurück. Nur lesbar [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Rückgabe:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


Gibt das PictureFillFormat-Objekt für einen Bildrahmen zurück. Nur lesbar [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


Gibt die Skalierung der Höhe (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben float.

**Rückgabe:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


Gibt die Skalierung der Höhe (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


Gibt die Skalierung der Breite (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben float.

**Rückgabe:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


Gibt die Skalierung der Breite (bezogen auf die ursprüngliche Bildgröße) des Bildrahmens zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |