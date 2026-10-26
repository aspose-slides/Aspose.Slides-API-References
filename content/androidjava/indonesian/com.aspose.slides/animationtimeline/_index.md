---
title: AnimationTimeLine
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili garis waktu animasi.
type: docs
url: /id/com.aspose.slides/animationtimeline/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Mewakili garis waktu animasi.
## Metode

| Method | Deskripsi |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Mengembalikan koleksi urutan interaktif. |
| [getMainSequence()](#getMainSequence--) | Mengembalikan urutan utama yang mungkin hanya berisi koleksi efek utama. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Mengembalikan koleksi animasi teks. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Mengembalikan koleksi urutan interaktif. Urutan ini hanya dapat berisi efek yang dipicu dengan "klik pada bentuk" dengan bentuk target yang ditentukan. Baca-saja [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Mengembalikan:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Mengembalikan urutan utama yang mungkin hanya berisi koleksi efek utama. Baca-saja [ISequence](../../com.aspose.slides/isequence).

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Mengembalikan koleksi animasi teks. Baca-saja [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Mengembalikan:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)