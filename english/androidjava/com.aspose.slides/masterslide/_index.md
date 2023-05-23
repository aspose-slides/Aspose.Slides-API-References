---
title: MasterSlide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a master slide in a presentation.
type: docs
weight: 302
url: /androidjava/com.aspose.slides/masterslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Represents a master slide in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the master slide. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides. |
| [getTitleStyle()](#getTitleStyle--) | Returns the style of a title text. |
| [getBodyStyle()](#getBodyStyle--) | Returns the style of a body text. |
| [getOtherStyle()](#getOtherStyle--) | Returns the style of an other text. |
| [getLayoutSlides()](#getLayoutSlides--) | Returns the collection of child layout slides for this master slide. |
| [getPreserve()](#getPreserve--) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. |
| [getDependingSlides()](#getDependingSlides--) | Returns an array with all slides, which depend on this master slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Returns true if there exists at least one slide that depends on this master slide. |
| [getThemeManager()](#getThemeManager--) | Returns the theme manager. |
| [getName()](#getName--) | Returns or sets the name of a master slide. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a master slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the master slide. Read-only [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Returns:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Creates a new master slide based on the current one, applying an external theme to it and applies the created master slide to all dependent slides.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the external theme file (.thmx). |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - New themed MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```


Returns the style of a title text. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```


Returns the style of a body text. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```


Returns the style of an other text. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```


Returns the collection of child layout slides for this master slide. Read-only [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

You can access to alternative API for adding/inserting/removing/cloning layout slides by using ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Returns:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```


Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Read/write  boolean .

**Returns:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```


Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Returns an array with all slides, which depend on this master slide.

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Returns true if there exists at least one slide that depends on this master slide. Read-only  boolean .

**Returns:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Returns the theme manager. Read-only [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Returns:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```


Returns or sets the name of a master slide. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Returns or sets the name of a master slide. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns  false . Read/write  boolean .

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns  false . Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

