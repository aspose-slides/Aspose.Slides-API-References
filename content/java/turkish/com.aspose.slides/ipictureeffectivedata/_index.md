---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /tr/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Etkili resim özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz, [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) ve [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)'un bir parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImage()](#getImage--) | Gömülü görüntüyü döndürür. |
| [getLinkPathLong()](#getLinkPathLong--) | Bağlantılı görüntünün URL'sini döndürür. |
| [getImageTransform()](#getImageTransform--) | Görüntü dönüşüm efektlerinin koleksiyonunu döndürür. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Gömülü görüntüyü döndürür. Salt okunur [IPPImage](../../com.aspose.slides/ippimage).

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bağlantılı görüntünün URL'sini döndürür. Salt okunur String.

**Returns:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

Görüntü dönüşüm efektlerinin koleksiyonunu döndürür. Salt okunur [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Returns:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)