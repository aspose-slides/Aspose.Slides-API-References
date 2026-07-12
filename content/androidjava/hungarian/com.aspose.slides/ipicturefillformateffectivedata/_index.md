---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Változtathatatlan objektum, amely a képtöltés tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/ipicturefillformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Változtathatatlan objektum, amely a képtöltés tulajdonságait tartalmazza.

--------------------

Ez az interfész a(z) [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDpi()](#getDpi--) | Visszaadja a képet kitöltéshez használt dpi értékét. |
| [getPictureFillMode()](#getPictureFillMode--) | Visszaadja a képtöltés módját. |
| [getPicture()](#getPicture--) | Visszaadja a képet. |
| [getCropLeft()](#getCropLeft--) | Visszaadja a valós képszélesség százalékos arányát, amely a kép bal oldaláról van levágva. |
| [getCropTop()](#getCropTop--) | Visszaadja a valós képmagasság százalékos arányát, amely a kép tetejéről van levágva. |
| [getCropRight()](#getCropRight--) | Visszaadja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról van levágva. |
| [getCropBottom()](#getCropBottom--) | Visszaadja a valós képmagasság százalékos arányát, amely a kép aljáról van levágva. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Visszaadja a képet kitöltéshez használt dpi értékét. Csak olvasható int.

**Visszatér:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Visszaadja a képtöltés módját. Csak olvasható [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Visszatér:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Visszaadja a képet. Csak olvasható [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Visszatér:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Visszaadja a valós képszélesség százalékos arányát, amely a kép bal oldaláról van levágva. Csak olvasható float.

**Visszatér:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Visszaadja a valós képmagasság százalékos arányát, amely a kép tetejéről van levágva. Csak olvasható float.

**Visszatér:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Visszaadja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról van levágva. Csak olvasható float.

**Visszatér:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Visszaadja a valós képmagasság százalékos arányát, amely a kép aljáról van levágva. Csak olvasható float.

**Visszatér:**
float