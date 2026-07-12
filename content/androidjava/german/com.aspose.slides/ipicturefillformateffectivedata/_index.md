---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides für Android über Java API-Referenz
description: Unveränderliches Objekt, das die Eigenschaften der Bildfüllung enthält.
type: docs
url: /de/com.aspose.slides/ipicturefillformateffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Unveränderliches Objekt, das die Eigenschaften der Bildfüllung enthält.

--------------------

Diese Schnittstelle wird als Teil von [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDpi()](#getDpi--) | Gibt die DPI zurück, die zum Füllen eines Bildes verwendet wird. |
| [getPictureFillMode()](#getPictureFillMode--) | Gibt den Bildfüllmodus zurück. |
| [getPicture()](#getPicture--) | Gibt das Bild zurück. |
| [getCropLeft()](#getCropLeft--) | Gibt die Prozentzahl der tatsächlichen Bildbreite zurück, die links vom Bild abgeschnitten wird. |
| [getCropTop()](#getCropTop--) | Gibt die Prozentzahl der tatsächlichen Bildhöhe zurück, die oben vom Bild abgeschnitten wird. |
| [getCropRight()](#getCropRight--) | Gibt die Prozentzahl der tatsächlichen Bildbreite zurück, die rechts vom Bild abgeschnitten wird. |
| [getCropBottom()](#getCropBottom--) | Gibt die Prozentzahl der tatsächlichen Bildhöhe zurück, die unten vom Bild abgeschnitten wird. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Gibt die DPI zurück, die zum Füllen eines Bildes verwendet wird. Nur lesend int.

**Rückgabe:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Gibt den Bildfüllmodus zurück. Nur lesend [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Rückgabe:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Gibt das Bild zurück. Nur lesend [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Rückgabe:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Gibt die Prozentzahl der tatsächlichen Bildbreite zurück, die links vom Bild abgeschnitten wird. Nur lesend float.

**Rückgabe:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Gibt die Prozentzahl der tatsächlichen Bildhöhe zurück, die oben vom Bild abgeschnitten wird. Nur lesend float.

**Rückgabe:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Gibt die Prozentzahl der tatsächlichen Bildbreite zurück, die rechts vom Bild abgeschnitten wird. Nur lesend float.

**Rückgabe:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Gibt die Prozentzahl der tatsächlichen Bildhöhe zurück, die unten vom Bild abgeschnitten wird. Nur lesend float.

**Rückgabe:**
float