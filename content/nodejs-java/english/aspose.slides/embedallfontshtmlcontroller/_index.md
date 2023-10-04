---
title: EmbedAllFontsHtmlController
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/embedallfontshtmlcontroller/
---

## EmbedAllFontsHtmlController class

 The formatting controller class to use for embedding all presentation fonts in WOFF format.
 
| [EmbedAllFontsHtmlController]() | Creates new instance |

### Result
EmbedAllFontsHtmlController


---


| [EmbedAllFontsHtmlController](java.lang.String[]) | Creates new instance |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Fonts to be excluded from embedding |

### Result
EmbedAllFontsHtmlController


---



## Functions

| Name | Description |
| --- | --- |
| [writeAllFonts]([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | Write all fonts contained in Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| presentation | [Presentation](../../presentation) | Presentation which being currently rendered. |


---


| [writeDocumentEnd]([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | Called to write html document footer. Called once per presentation conversion. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| presentation | [Presentation](../../presentation) | Presentation which being currently rendered. |


---


| [writeDocumentStart]([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | Called to write html document header. Called once per presentation conversion. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| presentation | [Presentation](../../presentation) | Presentation which being currently rendered. |


---


| [writeFont]([HtmlGenerator](../htmlgenerator), [FontData](../fontdata), [FontData](../fontdata), String, String, byte[]) | Writes data as base64 into HTML document itself |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | HTML generator |
| originalFont | [FontData](../fontdata) | Font to be serialized |
| substitutedFont | [FontData](../fontdata) | Substituted font (if font substitution occured), null otherwise |
| fontStyle | String | Font style |
| fontWeight | String | Font weight |
| fontData | byte[] | Font data |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [LegacyDiagram](../legacydiagram)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [LegacyDiagram](../../legacydiagram) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [Connector](../connector)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Connector](../../connector) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [GraphicalObject](../graphicalobject)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [GraphicalObject](../../graphicalobject) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [Shape](../shape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Shape](../../shape) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [Ink](../ink)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Ink](../../ink) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [GroupShape](../groupshape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [GroupShape](../../groupshape) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [SmartArtShape](../smartartshape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SmartArtShape](../../smartartshape) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [SummaryZoomSection](../summaryzoomsection)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SummaryZoomSection](../../summaryzoomsection) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [ZoomObject](../zoomobject)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [ZoomObject](../../zoomobject) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [SmartArt](../smartart)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SmartArt](../../smartart) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [VideoFrame](../videoframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [VideoFrame](../../videoframe) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [PictureFrame](../pictureframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [PictureFrame](../../pictureframe) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [ZoomFrame](../zoomframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [ZoomFrame](../../zoomframe) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [AutoShape](../autoshape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [AutoShape](../../autoshape) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [OleObjectFrame](../oleobjectframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [OleObjectFrame](../../oleobjectframe) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [SectionZoomFrame](../sectionzoomframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SectionZoomFrame](../../sectionzoomframe) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [AudioFrame](../audioframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [AudioFrame](../../audioframe) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [Chart](../chart)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Chart](../../chart) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [Table](../table)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Table](../../table) | Shape which is rendered last. |


---


| [writeShapeEnd]([HtmlGenerator](../htmlgenerator), [SummaryZoomFrame](../summaryzoomframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SummaryZoomFrame](../../summaryzoomframe) | Shape which is rendered last. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [LegacyDiagram](../legacydiagram)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [LegacyDiagram](../../legacydiagram) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [Connector](../connector)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Connector](../../connector) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [GraphicalObject](../graphicalobject)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [GraphicalObject](../../graphicalobject) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [Shape](../shape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Shape](../../shape) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [Ink](../ink)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Ink](../../ink) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [GroupShape](../groupshape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [GroupShape](../../groupshape) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [SmartArtShape](../smartartshape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SmartArtShape](../../smartartshape) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [SummaryZoomSection](../summaryzoomsection)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SummaryZoomSection](../../summaryzoomsection) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [ZoomObject](../zoomobject)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [ZoomObject](../../zoomobject) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [SmartArt](../smartart)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SmartArt](../../smartart) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [VideoFrame](../videoframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [VideoFrame](../../videoframe) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [PictureFrame](../pictureframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [PictureFrame](../../pictureframe) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [ZoomFrame](../zoomframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [ZoomFrame](../../zoomframe) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [AutoShape](../autoshape)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [AutoShape](../../autoshape) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [OleObjectFrame](../oleobjectframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [OleObjectFrame](../../oleobjectframe) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [SectionZoomFrame](../sectionzoomframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SectionZoomFrame](../../sectionzoomframe) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [AudioFrame](../audioframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [AudioFrame](../../audioframe) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [Chart](../chart)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Chart](../../chart) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [Table](../table)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [Table](../../table) | Shape which is about to render. |


---


| [writeShapeStart]([HtmlGenerator](../htmlgenerator), [SummaryZoomFrame](../summaryzoomframe)) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| shape | [SummaryZoomFrame](../../summaryzoomframe) | Shape which is about to render. |


---


| [writeSlideEnd]([HtmlGenerator](../htmlgenerator), [Slide](../slide)) | Called to write html slide footer. Called once per each of slides. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| slide | [Slide](../../slide) | Slide which being currently rendered. |


---


| [writeSlideStart]([HtmlGenerator](../htmlgenerator), [Slide](../slide)) | Called to write html slide header. Called once per each of slides. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Output object. |
| slide | [Slide](../../slide) | Slide which being currently rendered. |


---


