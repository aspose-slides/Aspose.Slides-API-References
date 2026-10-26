---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /it/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Oggetto immutabile che contiene le proprietà effettive dell'immagine.

--------------------

Questa interfaccia è utilizzata come parte di [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) e [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImage()](#getImage--) | Restituisce l'immagine incorporata. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce l'URL dell'immagine collegata. |
| [getImageTransform()](#getImageTransform--) | Restituisce la collezione di effetti di trasformazione dell'immagine. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Restituisce l'immagine incorporata. Solo lettura [IPPImage](../../com.aspose.slides/ippimage).

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Restituisce l'URL dell'immagine collegata. Solo lettura String.

**Restituisce:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Restituisce la collezione di effetti di trasformazione dell'immagine. Solo lettura [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Restituisce:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)