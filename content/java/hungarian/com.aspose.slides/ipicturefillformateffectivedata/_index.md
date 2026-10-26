---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides for Java API referencia
description: Megváltoztathatatlan objektum, amely a képkitöltés tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/ipicturefillformateffectivedata/
---
**Az összes implementált interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Megváltoztathatatlan objektum, amely a képkitöltés tulajdonságait tartalmazza.

--------------------

Ez az interfész a [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDpi()](#getDpi--) | Visszaadja a képet kitöltéshez használt dpi értéket. |
| [getPictureFillMode()](#getPictureFillMode--) | Visszaadja a képkitöltés módját. |
| [getPicture()](#getPicture--) | Visszaadja a képet. |
| [getCropLeft()](#getCropLeft--) | Visszaadja a valós képszélesség százalékos arányát, amely a kép bal oldaláról levágásra került. |
| [getCropTop()](#getCropTop--) | Visszaadja a valós képmagasság százalékos arányát, amely a kép felső részéről levágásra került. |
| [getCropRight()](#getCropRight--) | Visszaadja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról levágásra került. |
| [getCropBottom()](#getCropBottom--) | Visszaadja a valós képmagasság százalékos arányát, amely a kép alsó részéről levágásra került. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Visszaadja a képet kitöltéshez használt dpi értéket. Csak olvasható int.

**Visszatér:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Visszaadja a képkitöltés módját. Csak olvasható [PictureFillMode](../../com.aspose.slides/picturefillmode).

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


Visszaadja a valós képszélesség százalékos arányát, amely a kép bal oldaláról levágásra került. Csak olvasható float.

**Visszatér:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Visszaadja a valós képmagasság százalékos arányát, amely a kép felső részéről levágásra került. Csak olvasható float.

**Visszatér:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Visszaadja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról levágásra került. Csak olvasható float.

**Visszatér:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Visszaadja a valós képmagasság százalékos arányát, amely a kép alsó részéről levágásra került. Csak olvasható float.

**Visszatér:**
float