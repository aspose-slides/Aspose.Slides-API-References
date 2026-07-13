---
title: IPictureFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en ram med en bild inuti.
type: docs
url: /sv/com.aspose.slides/ipictureframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Representerar en ram med en bild inuti.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Returnerar PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | Returnerar PictureFillFormat-objektet för en bildram. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Returnerar eller anger skalan för höjden (relativt originalbildens storlek) för bildramen. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Returnerar eller anger skalan för höjden (relativt originalbildens storlek) för bildramen. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Returnerar eller anger skalan för bredden (relativt originalbildens storlek) för bildramen. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Returnerar eller anger skalan för bredden (relativt originalbildens storlek) för bildramen. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Returnerar PictureFrame's locks. Skrivskyddad [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Returnerar:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Returnerar PictureFillFormat-objektet för en bildram. Skrivskyddad [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Returnerar eller anger skalan för höjden (relativt originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float.

**Returnerar:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Returnerar eller anger skalan för höjden (relativt originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Returnerar eller anger skalan för bredden (relativt originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float.

**Returnerar:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Returnerar eller anger skalan för bredden (relativt originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |