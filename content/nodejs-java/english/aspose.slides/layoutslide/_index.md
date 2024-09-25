---
title: LayoutSlide
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/layoutslide/
---

## LayoutSlide class

 Represents a layout slide.
 
### getDependingSlides {#getDependingSlides}

| Name | Description |
| --- | --- |
| getDependingSlides () | Returns an array with all slides, which depend on this layout slide. |

 **Returns:**
[Slide](../slide)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Name | Description |
| --- | --- |
| getHeaderFooterManager () | Returns HeaderFooter manager of the layout slide. Read-only ILayoutSlideHeaderFooterManager. |

 **Returns:**
[LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager)


---


### getLayoutType {#getLayoutType}

| Name | Description |
| --- | --- |
| getLayoutType () | Returns layout type of this layout slide. Read-only SlideLayoutType. |

 **Returns:**
byte


---


### getMasterSlide {#getMasterSlide}

| Name | Description |
| --- | --- |
| getMasterSlide () | Returns or sets the master slide for a layout. Read/write IMasterSlide. |

 **Returns:**
[MasterSlide](../masterslide)


---


### getPlaceholderManager {#getPlaceholderManager}

| Name | Description |
| --- | --- |
| getPlaceholderManager () | Returns the placeholder manager of the layout slide. Read-only ILayoutPlaceholderManager. |

 **Returns:**
[LayoutPlaceholderManager](../layoutplaceholdermanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes () | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |

 **Returns:**
boolean


---


### getThemeManager {#getThemeManager}

| Name | Description |
| --- | --- |
| getThemeManager () | Returns the overriding theme manager. Read-only IOverrideThemeManager. |

 **Returns:**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [NotesSlideThemeManager](../notesslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager)


---


### hasDependingSlides {#hasDependingSlides}

| Name | Description |
| --- | --- |
| hasDependingSlides () | Returns true if there exists at least one slide that depends on this layout slide. Read-only boolean. |

 **Returns:**
boolean


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes layout from presentation. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is already removed from presentation or if layout is used in presentation (its HasDependingSlides property is true). To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. |


---


### setMasterSlide {#setMasterSlide}

| Name | Description |
| --- | --- |
| setMasterSlide ([MasterSlide](../masterslide)) | Returns or sets the master slide for a layout. Read/write IMasterSlide. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |


---


