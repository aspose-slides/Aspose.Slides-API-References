---
title: ISlidesPicture
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir sunumda bir resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/islidespicture/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Bir sunumda bir resmi temsil eder.

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getImage()](#getImage--) | Gömülü resmi döndürür veya ayarlar. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Gömülü resmi döndürür veya ayarlar. |
| [getLinkPathLong()](#getLinkPathLong--) | Bağlantılı resmin URL'sini döndürür veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bağlantılı resmin URL'sini döndürür veya ayarlar. |
| [getImageTransform()](#getImageTransform--) | Görüntü dönüşüm efektlerinin koleksiyonunu döndürür. |

### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Gömülü resmi döndürür veya ayarlar. Okuma/Yazma [IPPImage](../../com.aspose.slides/ippimage).

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Gömülü resmi döndürür veya ayarlar. Okuma/Yazma [IPPImage](../../com.aspose.slides/ippimage).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bağlantılı resmin URL'sini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Bağlantılı resmin URL'sini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Görüntü dönüşüm efektlerinin koleksiyonunu döndürür. Salt Okunur [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Döndürür:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)