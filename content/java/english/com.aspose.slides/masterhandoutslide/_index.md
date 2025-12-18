---
title: MasterHandoutSlide
second_title: Aspose.Slides for Java API Reference
description: Represents master slide for handouts.
type: docs
url: /com.aspose.slides/masterhandoutslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Represents master slide for handouts.
## Methods

| Method | Description |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the master handout slide. |
| [getThemeManager()](#getThemeManager--) | Returns the theme manager. |
| [getDrawingGuides()](#getDrawingGuides--) | Returns a collection of drawing guides for the master handout slide. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the master handout slide. Read-only [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Returns:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Returns the theme manager. Read-only [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Returns:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Returns a collection of drawing guides for the master handout slide. Read-only [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Adding the new horizontal drawing guide above the slide center
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
