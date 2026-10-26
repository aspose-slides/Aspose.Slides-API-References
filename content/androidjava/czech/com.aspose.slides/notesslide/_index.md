---
title: NotesSlide
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje poznámkový snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/notesslide/
---
**Dědění:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Všechny implementované rozhraní:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Reprezentuje poznámkový snímek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter poznámkového snímku. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Vrací TextFrame s textem poznámek, pokud existuje. |
| [getThemeManager()](#getThemeManager--) | Vrací přepisující správce motivu. |
| [getParentSlide()](#getParentSlide--) | Vrací rodičovský snímek. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter poznámkového snímku. Pouze pro čtení [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Vrací:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Vrací TextFrame s textem poznámek, pokud existuje. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Vrací přepisující správce motivu. Pouze pro čtení [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Vrací:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Vrací rodičovský snímek. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. Boolean čtení/zápis.

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích či ne. Boolean čtení/zápis.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |