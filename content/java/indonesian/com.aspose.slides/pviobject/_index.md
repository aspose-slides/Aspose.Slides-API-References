---
title: PVIObject
second_title: Referensi API Aspose.Slides untuk Java
description: Mengkapsulkan infrastruktur layanan dasar untuk objek yang dapat menjadi subjek pewarisan nilai properti.
type: docs
url: /id/com.aspose.slides/pviobject/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Mengkapsulkan infrastruktur layanan dasar untuk objek yang dapat menjadi subjek pewarisan nilai properti.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Membandingkan dengan objek yang ditentukan. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Mengembalikan parent IPresentationComponent. Hanya-baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```



**Mengembalikan:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Mengembalikan presentasi. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[Presentation](../../com.aspose.slides/presentation)
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

Mengembalikan kode hash.

**Mengembalikan:**
int - Kode hash.