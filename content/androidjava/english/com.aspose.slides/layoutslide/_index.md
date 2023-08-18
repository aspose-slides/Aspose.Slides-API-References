---
title: LayoutSlide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a layout slide.
type: docs
weight: 261
url: /com.aspose.slides/layoutslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Represents a layout slide.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the layout slide. |
| [getMasterSlide()](#getMasterSlide--) | Returns or sets the master slide for a layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Returns or sets the master slide for a layout. |
| [remove()](#remove--) | Removes layout from presentation. |
| [getThemeManager()](#getThemeManager--) | Returns the overriding theme manager. |
| [getLayoutType()](#getLayoutType--) | Returns layout type of this layout slide. |
| [getDependingSlides()](#getDependingSlides--) | Returns an array with all slides, which depend on this layout slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Returns true if there exists at least one slide that depends on this layout slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the layout slide. Read-only [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Returns:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Returns or sets the master slide for a layout. Read/write [IMasterSlide](../../com.aspose.slides/imasterslide).

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Returns or sets the master slide for a layout. Read/write [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Removes layout from presentation.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Returns the overriding theme manager. Read-only [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returns:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Returns layout type of this layout slide. Read-only [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Returns:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Returns an array with all slides, which depend on this layout slide.

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Returns true if there exists at least one slide that depends on this layout slide. Read-only boolean.

**Returns:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

