---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Notes slide manager.
type: docs
weight: 936
url: /androidjava/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
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
public abstract INotesSlide getNotesSlide()
```


Returns the notes slide for the current slide. Returns null if slide doesn't have notes slide. Read-only [INotesSlide](../../com.aspose.slides/inotesslide).

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Returns the notes slide for the current slide, creating one if there isn't.

**Returns:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Removes notes slide of the current slide.

