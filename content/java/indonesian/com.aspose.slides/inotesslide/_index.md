---
title: INotesSlide
second_title: Referensi API Java Aspose.Slides
description: Mewakili slide catatan dalam presentasi.
type: docs
url: /id/com.aspose.slides/inotesslide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Mewakili slide catatan dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan HeaderFooter manager dari slide catatan. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Mengembalikan TextFrame dengan teks catatan jika ada. |
| [getParentSlide()](#getParentSlide--) | Mengembalikan ParentSlide Hanya-baca [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan HeaderFooter manager dari slide catatan. Hanya-baca [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Mengembalikan:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


Mengembalikan TextFrame dengan teks catatan jika ada. Hanya-baca [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


Mengembalikan ParentSlide Hanya-baca [ISlide](../../com.aspose.slides/islide).

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)