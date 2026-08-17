---
title: Picture
second_title: Aspose.Slides için Java API Referansı
description: Bir sunumdaki resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/picture/
---
**Miras:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Bir sunumdaki resmi temsil eder.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Gömülü resmi getirir veya ayarlar. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Gömülü resmi getirir veya ayarlar. |
| [getLinkPathLong()](#getLinkPathLong--) | Bağlantılı resmin URL'sini getirir veya ayarlar. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bağlantılı resmin URL'sini getirir veya ayarlar. |
| [getImageTransform()](#getImageTransform--) | Resim dönüşüm efektleri koleksiyonunu getirir. |
| [getPresentation()](#getPresentation--) | Sunumu getirir. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesne ile karşılaştırır. |
| [hashCode()](#hashCode--) | Hash değerini getirir. |
| [getSlide()](#getSlide--) | Resmin üst slaytını getirir. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini getirir. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versiyon. Yalnızca okunur long.

**Döndürür:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent üst nesnesini getirir. Yalnızca okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Gömülü resmi getirir veya ayarlar. Okunur/Yazılabilir [IPPImage](../../com.aspose.slides/ippimage).

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Gömülü resmi getirir veya ayarlar. Okunur/Yazılabilir [IPPImage](../../com.aspose.slides/ippimage).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Bağlantılı resmin URL'sini getirir veya ayarlar. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Bağlantılı resmin URL'sini getirir veya ayarlar. Okunur/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Resim dönüşüm efektleri koleksiyonunu getirir. Yalnızca okunur [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Döndürür:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Sunumu getirir. Yalnızca okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen nesne ile karşılaştırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak nesne. |

**Döndürür:**
boolean - Nesneler eşitse true, aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash değerini getirir.

**Döndürür:**
int - Hash.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Resmin üst slaytını getirir. Yalnızca okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)