---
title: IPictureFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een frame met een afbeelding voor.
type: docs
url: /nl/com.aspose.slides/ipictureframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Stelt een frame met een afbeelding voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Retourneert PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | Retourneert het PictureFillFormat-object voor een picture frame. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Retourneert PictureFrame's locks. Alleen-lezen [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Retour:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Retourneert het PictureFillFormat-object voor een picture frame. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. Waarde 1.0 komt overeen met 100%. Lezen/Schrijven float.

**Retour:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. Waarde 1.0 komt overeen met 100%. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. Waarde 1.0 komt overeen met 100%. Lezen/Schrijven float.

**Retour:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame. Waarde 1.0 komt overeen met 100%. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |