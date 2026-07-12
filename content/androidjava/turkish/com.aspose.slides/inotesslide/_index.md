---
title: INotesSlide
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir sunumdaki not slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/inotesslide/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Bir sunumdaki not slaytını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Not slaytının HeaderFooter yöneticisini döndürür. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Varsa, not metni içeren bir TextFrame döndürür. |
| [getParentSlide()](#getParentSlide--) | Salt okunur bir ParentSlide [ISlide](../../com.aspose.slides/islide) döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Not slaytının HeaderFooter yöneticisini döndürür. Salt okunur [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Döndürür:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


Varsa, not metni içeren bir TextFrame döndürür. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


Salt okunur bir ParentSlide [ISlide](../../com.aspose.slides/islide) döndürür.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)