---
title: IMasterSlide
second_title: Aspose.Slides for Java API Reference
description:  Represents a master slide in a presentation.
type: docs
weight: 871
url: /java/com.aspose.slides/imasterslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Represents a master slide in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the master slide. |
| [getTitleStyle()](#getTitleStyle--) | Returns the style of a title text. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides. |
| [getBodyStyle()](#getBodyStyle--) | Returns the style of a body text. |
| [getOtherStyle()](#getOtherStyle--) | Returns the style of an other text. |
| [getLayoutSlides()](#getLayoutSlides--) | Returns the collection of child layout slides for this master slide. |
| [getPreserve()](#getPreserve--) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. |
| [hasDependingSlides()](#hasDependingSlides--) | Returns true if there exists at least one slide that depends on this master slide. |
| [getDependingSlides()](#getDependingSlides--) | Returns an array with all slides, which depend on this master slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the master slide. Read-only [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Returns:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Returns the style of a title text. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the external theme file (.thmx). |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - New themed MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Returns the style of a body text. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Returns the style of an other text. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Returns the collection of child layout slides for this master slide. Read-only [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

You can access to alternative API for adding/inserting/removing/cloning layout slides by using ([IPresentation\#getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Returns:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call [IMasterSlideCollection\#removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Read/write boolean.

**Returns:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call [IMasterSlideCollection\#removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Returns true if there exists at least one slide that depends on this master slide. Read-only boolean.

**Returns:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Returns an array with all slides, which depend on this master slide.

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../com.aspose.slides/islide), which depend on this master slide
