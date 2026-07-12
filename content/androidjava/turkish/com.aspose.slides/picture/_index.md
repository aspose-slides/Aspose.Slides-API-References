---
title: Picture
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunumdaki resmi temsil eder.
type: docs
url: /tr/com.aspose.slides/picture/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
| [getImage()](#getImage--) | Returns or sets the embedded image. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returns or sets the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns of sets linked image's URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns of sets linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
| [getPresentation()](#getPresentation--) | Returns the presentation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares with specified object. |
| [hashCode()](#hashCode--) | Returns hash. |
| [getSlide()](#getSlide--) | Returns the parent slide of a picture. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Parent IPresentationComponent nesnesini döndürür. Salt okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Gömülü resmi döndürür veya ayarlar. Okunabilir/Yazılabilir [IPPImage](../../com.aspose.slides/ippimage).

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Gömülü resmi döndürür veya ayarlar. Okunabilir/Yazılabilir [IPPImage](../../com.aspose.slides/ippimage).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Bağlantılı resmin URL'sini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Bağlantılı resmin URL'sini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Görüntü dönüşüm etkileri koleksiyonunu döndürür. Salt okunur [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Döndürür:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Sunumu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen nesne ile karşılaştırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak nesne. |

**Döndürür:**
boolean - Nesneler eşitse true, aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Karma değerini döndürür.

**Döndürür:**
int - Karma.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Resmin ebeveyn slaydını döndürür. Salt okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)