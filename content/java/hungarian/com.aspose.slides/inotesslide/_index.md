---
title: INotesSlide
second_title: Aspose.Slides for Java API referencia
description: Egy jegyzetdia a prezentációban.
type: docs
url: /hu/com.aspose.slides/inotesslide/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Egy jegyzetdia a prezentációban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a jegyzetdia HeaderFooter managerét. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Visszaad egy TextFrame-et a jegyzet szöveggel, ha van. |
| [getParentSlide()](#getParentSlide--) | Visszaad egy ParentSlide-t csak olvasható [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Visszaadja a jegyzetdia HeaderFooter managerét. Csak olvasható [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Visszaad:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


Visszaad egy TextFrame-et a jegyzet szöveggel, ha van. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszaad:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


Visszaad egy ParentSlide-t csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszaad:**
[ISlide](../../com.aspose.slides/islide)