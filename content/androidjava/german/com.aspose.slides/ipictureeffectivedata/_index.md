---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Unveränderliches Objekt, das effektive Bildeigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Unveränderliches Objekt, das effektive Bildeigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) und [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImage()](#getImage--) | Gibt das eingebettete Bild zurück. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt die URL des verknüpften Bildes zurück. |
| [getImageTransform()](#getImageTransform--) | Gibt die Sammlung der Bildtransformations-Effekte zurück. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Gibt das eingebettete Bild zurück. Nur lesbar [IPPImage](../../com.aspose.slides/ippimage).

**Rückgabe:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Gibt die URL des verknüpften Bildes zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Gibt die Sammlung der Bildtransformations-Effekte zurück. Nur lesbar [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Rückgabe:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)