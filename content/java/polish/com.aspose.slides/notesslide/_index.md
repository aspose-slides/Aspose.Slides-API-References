---
title: NotesSlide
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje slajd notatek w prezentacji.
type: docs
url: /pl/com.aspose.slides/notesslide/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**  
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)  
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Reprezentuje slajd notatek w prezentacji.

## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżer HeaderFooter slajdu notatek. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Zwraca TextFrame z tekstem notatek, jeśli jest dostępny. |
| [getThemeManager()](#getThemeManager--) | Zwraca nadpisujący menedżer motywu. |
| [getParentSlide()](#getParentSlide--) | Zwraca slajd nadrzędny. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie wzorca mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie wzorca mają być wyświetlane na slajdach, czy nie. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżer HeaderFooter slajdu notatek. Tylko do odczytu [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Zwraca:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)

### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Zwraca TextFrame z tekstem notatek, jeśli jest dostępny. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Zwraca nadpisujący menedżer motywu. Tylko do odczytu [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

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

Określa, czy kształty na slajdzie wzorca mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean.

**Zwraca:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Określa, czy kształty na slajdzie wzorca mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |