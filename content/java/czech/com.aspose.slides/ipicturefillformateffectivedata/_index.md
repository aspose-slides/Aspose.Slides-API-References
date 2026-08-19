---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides pro Java – referenční příručka API
description: Neměnný objekt, který obsahuje vlastnosti výplně obrázku.
type: docs
url: /cs/com.aspose.slides/ipicturefillformateffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje vlastnosti výplně obrázku.

--------------------

Toto rozhraní se používá jako součást [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Metody

| Metoda | Popis |
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


Returns the dpi which is used to fill a picture. Pouze ke čtení int.

**Vrací:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Returns the picture fill mode. Pouze ke čtení [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Vrací:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Returns the picture. Pouze ke čtení [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Vrací:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Returns the number of percents of real image width that are cropped off the left of the picture. Pouze ke čtení float.

**Vrací:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Returns the number of percents of real image height that are cropped off the top of the picture. Pouze ke čtení float.

**Vrací:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Returns the number of percents of real image width that are cropped off the right of the picture. Pouze ke čtení float.

**Vrací:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Returns the number of percents of real image height that are cropped off the bottom of the picture. Pouze ke čtení float.

**Vrací:**
float