---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides dla Java – odniesienie API
description: Niezmienny obiekt zawierający właściwości wypełnienia obrazu.
type: docs
url: /pl/com.aspose.slides/ipicturefillformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Niezmienny obiekt zawierający właściwości wypełnienia obrazu.

--------------------

Ten interfejs jest używany jako część [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getDpi()](#getDpi--) | Returns the dpi which is used to fill a picture. |
| [getPictureFillMode()](#getPictureFillMode--) | Returns the picture fill mode. |
| [getPicture()](#getPicture--) | Returns the picture. |
| [getCropLeft()](#getCropLeft--) | Returns the number of percents of real image width that are cropped off the left of the picture. |
| [getCropTop()](#getCropTop--) | Returns the number of percents of real image height that are cropped off the top of the picture. |
| [getCropRight()](#getCropRight--) | Returns the number of percents of real image width that are cropped off the right of the picture. |
| [getCropBottom()](#getCropBottom--) | Returns the number of percents of real image height that are cropped off the bottom of the picture. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Zwraca dpi używany do wypełniania obrazu. Read-only int.

**Zwraca:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Zwraca tryb wypełnienia obrazu. Read-only [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Zwraca:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Zwraca obraz. Read-only [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Zwraca:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Zwraca liczbę procent rzeczywistej szerokości obrazu, które są obcięte po lewej stronie obrazu. Read-only float.

**Zwraca:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Zwraca liczbę procent rzeczywistej wysokości obrazu, które są obcięte u góry obrazu. Read-only float.

**Zwraca:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Zwraca liczbę procent rzeczywistej szerokości obrazu, które są obcięte po prawej stronie obrazu. Read-only float.

**Zwraca:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Zwraca liczbę procent rzeczywistej wysokości obrazu, które są obcięte u dołu obrazu. Read-only float.

**Zwraca:**
float