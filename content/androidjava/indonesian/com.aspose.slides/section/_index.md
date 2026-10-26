---
title: Section
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili bagian slide.
type: docs
url: /id/com.aspose.slides/section/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Mewakili bagian slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Nama bagian. |
| [setName(String value)](#setName-java.lang.String-) | Nama bagian. |
| [getSectionId()](#getSectionId--) | ID Bagian. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Mengembalikan slide pertama dari bagian. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Mengembalikan daftar slide dalam bagian. |
### getName() {#getName--}
```
public final String getName()
```


Nama bagian.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Nama bagian.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


ID Bagian.

**Mengembalikan:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Mengembalikan slide pertama dari bagian.

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Mengembalikan daftar slide dalam bagian.

**Mengembalikan:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Daftar slide.