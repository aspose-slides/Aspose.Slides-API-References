---
title: AnimationTimeLine
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili timeline animasi.
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

Mewakili timeline animasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Mengembalikan koleksi urutan interaktif. |
| [getMainSequence()](#getMainSequence--) | Mengembalikan urutan utama yang mungkin hanya berisi koleksi efek utama. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Mengembalikan koleksi animasi teks. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Mengembalikan koleksi urutan interaktif. Urutan ini mungkin hanya berisi efek dengan "klik pada bentuk" dengan target bentuk yang ditentukan. Baca-saja [ISequenceCollection](../../com.aspose.slides/isequencecollection).

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