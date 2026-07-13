---
title: IPictureFrame
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Reprezentuje rám s obrázkem uvnitř.
type: docs
url: /cs/com.aspose.slides/ipictureframe/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Reprezentuje rám s obrázkem uvnitř.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Vrací zámky PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Vrací objekt PictureFillFormat pro rám s obrázkem. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámu s obrázkem. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámu s obrázkem. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámu s obrázkem. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámu s obrázkem. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


Vrací zámky PictureFrame. Pouze ke čtení [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Vrací:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


Vrací objekt PictureFillFormat pro rám s obrázkem. Pouze ke čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámu s obrázkem. Hodnota 1.0 odpovídá 100 %. Čtení/zápis float.

**Vrací:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámu s obrázkem. Hodnota 1.0 odpovídá 100 %. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámu s obrázkem. Hodnota 1.0 odpovídá 100 %. Čtení/zápis float.

**Vrací:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámu s obrázkem. Hodnota 1.0 odpovídá 100 %. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |