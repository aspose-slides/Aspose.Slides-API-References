---
title: Picture
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili gambar dalam sebuah presentasi.
type: docs
url: /id/com.aspose.slides/picture/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Mewakili gambar dalam sebuah presentasi.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Mengembalikan atau mengatur gambar yang disematkan. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Mengembalikan atau mengatur gambar yang disematkan. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan atau mengatur URL gambar yang ditautkan. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan atau mengatur URL gambar yang ditautkan. |
| [getImageTransform()](#getImageTransform--) | Mengembalikan koleksi efek transformasi gambar. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Membandingkan dengan objek yang ditentukan. |
| [hashCode()](#hashCode--) | Mengembalikan hash. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari gambar. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versi. Hanya baca long.

**Mengembalikan:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Mengembalikan IPresentationComponent induk. Hanya baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Mengembalikan atau mengatur gambar yang disematkan. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Mengembalikan atau mengatur gambar yang disematkan. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

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

Mengembalikan koleksi efek transformasi gambar. Hanya baca [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Mengembalikan:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi. Hanya baca [IPresentation](../../com.aspose.slides/ipresentation).

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
boolean - True jika objek sama, jika tidak false.

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

Mengembalikan slide induk dari gambar. Hanya baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)