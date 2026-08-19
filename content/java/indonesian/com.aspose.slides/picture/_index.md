---
title: Picture
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili gambar dalam presentasi.
type: docs
url: /id/com.aspose.slides/picture/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Mewakili gambar dalam presentasi.
## Metode

| Metode | Deskripsi |
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

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Mengembalikan IPresentationComponent induk. Hanya-baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Mengembalikan atau mengatur gambar yang tersemat. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Mengembalikan atau mengatur gambar yang tersemat. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Mengembalikan atau mengatur URL gambar yang ditautkan. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Mengembalikan atau mengatur URL gambar yang ditautkan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Mengembalikan koleksi efek transformasi gambar. Hanya-baca [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Mengembalikan:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Membandingkan dengan objek yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama, jika tidak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Mengembalikan hash.

**Mengembalikan:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari gambar. Hanya-baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)