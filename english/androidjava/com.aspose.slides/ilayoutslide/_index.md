---
title: ILayoutSlide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a layout slide.
type: docs
weight: 844
url: /androidjava/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Represents a layout slide.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the layout slide. |
| [getMasterSlide()](#getMasterSlide--) | Returns or sets the master slide for a layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Returns or sets the master slide for a layout. |
| [getLayoutType()](#getLayoutType--) | Returns layout type of this layout slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Returns true if there exists at least one slide that depends on this layout slide. |
| [getDependingSlides()](#getDependingSlides--) | Returns an array with all slides, which depend on this layout slide. |
| [remove()](#remove--) | Removes layout from presentation. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the layout slide. Read-only [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Returns:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Returns or sets the master slide for a layout. Read/write [IMasterSlide](../../com.aspose.slides/imasterslide).

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Returns or sets the master slide for a layout. Read/write [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Returns layout type of this layout slide. Read-only [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Returns:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Returns true if there exists at least one slide that depends on this layout slide. Read-only boolean.

**Returns:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Returns an array with all slides, which depend on this layout slide.

**Returns:**
com.aspose.slides.ISlide[] - Array with all slides, which depend on this layout slide
### remove() {#remove--}
```
public abstract void remove()
```


Removes layout from presentation.

