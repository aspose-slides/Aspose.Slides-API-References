---
title: NotesSlide
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir sunumdaki not slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/notesslide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Bir sunumdaki not slaytını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Not slaytının HeaderFooter yöneticisini döndürür. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Not metni varsa bir TextFrame döndürür. |
| [getThemeManager()](#getThemeManager--) | Geçersiz kılan tema yöneticisini döndürür. |
| [getParentSlide()](#getParentSlide--) | Üst slaytı döndürür. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Not slaytının HeaderFooter yöneticisini döndürür. Salt okunur [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Döndürür:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```


Not metni varsa bir TextFrame döndürür. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Geçersiz kılan tema yöneticisini döndürür. Salt okunur [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Döndürür:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```


Üst slaytı döndürür. Salt okunur [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |