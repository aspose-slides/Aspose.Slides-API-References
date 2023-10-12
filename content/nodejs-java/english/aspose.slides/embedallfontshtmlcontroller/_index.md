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


| [EmbedAllFontsHtmlController]([java.lang.String[]]) | Creates new instance |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | [java.lang.String[]] | Fonts to be excluded from embedding |

### Result
EmbedAllFontsHtmlController


---


| [writeAllFonts] ([HtmlGenerator], [Presentation]) | Write all fonts contained in Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| presentation | [Presentation] | Presentation which being currently rendered. |


---


| [writeDocumentEnd] ([HtmlGenerator], [Presentation]) | Called to write html document footer. Called once per presentation conversion. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| presentation | [Presentation] | Presentation which being currently rendered. |


---


| [writeDocumentStart] ([HtmlGenerator], [Presentation]) | Called to write html document header. Called once per presentation conversion. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| presentation | [Presentation] | Presentation which being currently rendered. |


---


| [writeFont] ([HtmlGenerator], [FontData], [FontData], [String], [String], [byte[]]) | Writes data as base64 into HTML document itself |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | HTML generator |
| originalFont | [FontData] | Font to be serialized |
| substitutedFont | [FontData] | Substituted font (if font substitution occured), null otherwise |
| fontStyle | [String] | Font style |
| fontWeight | [String] | Font weight |
| fontData | [byte[]] | Font data |


---


| [writeShapeEnd] ([HtmlGenerator], [LegacyDiagram]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [LegacyDiagram] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [Connector]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Connector] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [GraphicalObject]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [GraphicalObject] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [Shape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Shape] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [Ink]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Ink] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [GroupShape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [GroupShape] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [SmartArtShape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SmartArtShape] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [SummaryZoomSection]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SummaryZoomSection] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [ZoomObject]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [ZoomObject] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [SmartArt]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SmartArt] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [VideoFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [VideoFrame] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [PictureFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [PictureFrame] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [ZoomFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [ZoomFrame] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [AutoShape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [AutoShape] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [OleObjectFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [OleObjectFrame] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [SectionZoomFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SectionZoomFrame] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [AudioFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [AudioFrame] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [Chart]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Chart] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [Table]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Table] | Shape which is rendered last. |


---


| [writeShapeEnd] ([HtmlGenerator], [SummaryZoomFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SummaryZoomFrame] | Shape which is rendered last. |


---


| [writeShapeStart] ([HtmlGenerator], [LegacyDiagram]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [LegacyDiagram] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [Connector]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Connector] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [GraphicalObject]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [GraphicalObject] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [Shape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Shape] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [Ink]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Ink] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [GroupShape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [GroupShape] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [SmartArtShape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SmartArtShape] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [SummaryZoomSection]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SummaryZoomSection] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [ZoomObject]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [ZoomObject] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [SmartArt]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SmartArt] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [VideoFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [VideoFrame] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [PictureFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [PictureFrame] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [ZoomFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [ZoomFrame] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [AutoShape]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [AutoShape] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [OleObjectFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [OleObjectFrame] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [SectionZoomFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SectionZoomFrame] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [AudioFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [AudioFrame] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [Chart]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Chart] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [Table]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [Table] | Shape which is about to render. |


---


| [writeShapeStart] ([HtmlGenerator], [SummaryZoomFrame]) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| shape | [SummaryZoomFrame] | Shape which is about to render. |


---


| [writeSlideEnd] ([HtmlGenerator], [Slide]) | Called to write html slide footer. Called once per each of slides. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| slide | [Slide] | Slide which being currently rendered. |


---


| [writeSlideStart] ([HtmlGenerator], [Slide]) | Called to write html slide header. Called once per each of slides. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator] | Output object. |
| slide | [Slide] | Slide which being currently rendered. |


---


