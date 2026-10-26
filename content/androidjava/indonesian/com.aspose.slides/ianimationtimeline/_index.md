---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili garis waktu animasi.
type: docs
url: /id/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Mewakili garis waktu animasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Mengembalikan koleksi urutan interaktif. |
| [getMainSequence()](#getMainSequence--) | Mengembalikan urutan utama yang dapat berisi hanya koleksi efek utama. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Mengembalikan koleksi animasi teks. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Mengembalikan koleksi urutan interaktif. Urutan ini dapat berisi hanya efek dengan "klik pada bentuk" dengan target bentuk yang ditentukan. Hanya-baca [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Mengembalikan:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Mengembalikan urutan utama yang dapat berisi hanya koleksi efek utama. Hanya-baca [ISequence](../../com.aspose.slides/isequence).

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Mengembalikan koleksi animasi teks. Hanya-baca [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Mengembalikan:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)