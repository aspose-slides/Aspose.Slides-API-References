---
title: NotesSlide
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje slajd notatek w prezentacji.
type: docs
url: /pl/com.aspose.slides/notesslide/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Reprezentuje slajd notatek w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu notatek. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Zwraca obiekt TextFrame z tekstem notatek, jeśli istnieje. |
| [getThemeManager()](#getThemeManager--) | Zwraca nadrzędny theme manager. |
| [getParentSlide()](#getParentSlide--) | Zwraca slajd nadrzędny. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach, czy nie. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Zwraca menedżera HeaderFooter slajdu notatek. Tylko do odczytu [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Zwraca:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```


Zwraca obiekt TextFrame z tekstem notatek, jeśli istnieje. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Zwraca nadrzędny theme manager. Tylko do odczytu [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Zwraca:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```


Zwraca slajd nadrzędny. Tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |