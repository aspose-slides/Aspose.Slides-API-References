---
title: INotesSlide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a notes slide in a presentation.
type: docs
weight: 937
url: /com.aspose.slides/inotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Represents a notes slide in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the notes slide. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Returns a TextFrame with notes' text if there is one. |
| [getParentSlide()](#getParentSlide--) | Returns a ParentSlide Read-only [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the notes slide. Read-only [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Returns:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


Returns a TextFrame with notes' text if there is one. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


Returns a ParentSlide Read-only [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
