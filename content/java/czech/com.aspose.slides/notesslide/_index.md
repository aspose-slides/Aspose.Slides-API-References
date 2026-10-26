---
title: NotesSlide
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje snímek s poznámkami v prezentaci.
type: docs
url: /cs/com.aspose.slides/notesslide/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Všechny implementované rozhraní:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Reprezentuje snímek s poznámkami v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter snímku s poznámkami. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Vrací TextFrame s textem poznámek, pokud existuje. |
| [getThemeManager()](#getThemeManager--) | Vrací přepisující správce motivu. |
| [getParentSlide()](#getParentSlide--) | Vrací nadřazený snímek. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter snímku s poznámkami. Pouze pro čtení [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Návratová hodnota:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Vrací TextFrame s textem poznámek, pokud existuje. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Návratová hodnota:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Vrací přepisující správce motivu. Pouze pro čtení [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Návratová hodnota:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Vrací nadřazený snímek. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Návratová hodnota:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |