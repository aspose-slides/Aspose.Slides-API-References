---
title: NotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notes slide manager.
type: docs
weight: 379
url: /java/com.aspose.slides/notesslidemanager/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Notes slide manager.
## Methods

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returns the notes slide for the current slide. |
| [addNotesSlide()](#addNotesSlide--) | Returns the notes slide for the current slide, creating one if there isn't. |
| [removeNotesSlide()](#removeNotesSlide--) | Removes notes slide of the current slide. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Returns the notes slide for the current slide. Returns null if slide doesn't have notes slide. Read-only [INotesSlide](../../com.aspose.slides/inotesslide).

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Returns the notes slide for the current slide, creating one if there isn't.

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Removes notes slide of the current slide.

