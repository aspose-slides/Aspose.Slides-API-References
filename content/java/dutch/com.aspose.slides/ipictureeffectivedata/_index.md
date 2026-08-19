---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /nl/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Onveranderlijk object dat effectieve afbeeldingseigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) en [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImage()](#getImage--) | Retourneert de ingebedde afbeelding. |
| [getLinkPathLong()](#getLinkPathLong--) | Retourneert de URL van de gekoppelde afbeelding. |
| [getImageTransform()](#getImageTransform--) | Retourneert de collectie van afbeeldingstransformatie-effecten. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Retourneert de ingebedde afbeelding. Alleen-lezen [IPPImage](../../com.aspose.slides/ippimage).

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Retourneert de URL van de gekoppelde afbeelding. Alleen-lezen String.

**Retour:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Retourneert de collectie van afbeeldingstransformatie-effecten. Alleen-lezen [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Retour:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)