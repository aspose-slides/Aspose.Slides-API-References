---
title: INotesSlide
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumdaki not slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/inotesslide/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Bir sunumdaki not slaytını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Not slaytının HeaderFooter yöneticisini döndürür. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Varsa not metniyle bir TextFrame döndürür. |
| [getParentSlide()](#getParentSlide--) | Yalnızca okunur [ISlide](../../com.aspose.slides/islide) bir ParentSlide döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Not slaytının HeaderFooter yöneticisini döndürür. Yalnızca okunur [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Döndürür:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Varsa not metniyle bir TextFrame döndürür. Yalnızca okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Yalnızca okunur [ISlide](../../com.aspose.slides/islide) bir ParentSlide döndürür.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)