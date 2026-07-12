---
title: INotesSlide
second_title: Aspose.Slides for Android Java API Referencia
description: Egy jegyzetdia reprezentálása a prezentációban.
type: docs
url: /hu/com.aspose.slides/inotesslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Egy jegyzetdia reprezentálása a bemutatóban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a jegyzetdia HeaderFooter managerét. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Visszaad egy TextFrame-et a jegyzet szövegével, ha van. |
| [getParentSlide()](#getParentSlide--) | Visszaad egy ParentSlide csak olvasható [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a jegyzetdia HeaderFooter managerét. Csak olvasható [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Visszatér:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Visszaad egy TextFrame-et a jegyzet szövegével, ha van. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Visszaad egy ParentSlide csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)