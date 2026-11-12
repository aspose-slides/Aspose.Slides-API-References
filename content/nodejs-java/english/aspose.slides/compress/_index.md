---
title: Compress
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/compress/
---

## Compress class

 Represents a group of methods intended to compress  Presentation.
 
### Compress {#Compress}

| Name | Description |
| --- | --- |
| Compress() |  |

 **Returns:**
Compress


---


### compressEmbeddedFonts {#compressEmbeddedFonts}

| Name | Description |
| --- | --- |
| compressEmbeddedFonts ([Presentation](../presentation)) | Makes compression of the Presentation by removing unused characters from embedded fonts. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The presentation instance |


---


### compressImages {#compressImages}

| Name | Description |
| --- | --- |
| compressImages ([Presentation](../presentation), int) | Reduces the resolution of pictures in the presentation and deletes their cropped areas, similar to PowerPoint's "Compress Pictures" applied to all pictures. Pictures on slides, layout slides and master slides are processed, including pictures inside group shapes and picture fills of shapes. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | The presentation to process. |
| resolution | int | Target resolution relative to the size at which each picture is displayed. PicturesCompression#DocumentResolution leaves pictures unchanged. Pictures already at or below the target resolution are left unchanged; pictures are never upscaled. Not processed: slide backgrounds, table cell fills, charts, SmartArt, GIF images (to preserve animation), SVG and metafile (EMF/WMF) images. Cropped areas are removed permanently and cannot be restored in PowerPoint. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | presentation is null. |


---


### compressPresentation {#compressPresentation}

| Name | Description |
| --- | --- |
| compressPresentation ([Presentation](../presentation)) | Reduces the size of a presentation by applying all available compression steps: Removes unused master slides #removeUnusedMasterSlides(Presentation).Removes unused layout slides #removeUnusedLayoutSlides(Presentation).Keeps only the glyphs actually used in embedded fonts #compressEmbeddedFonts(Presentation).Reduces picture resolution to 150 DPI and deletes cropped areas of pictures #compressImages(IPresentation,int). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | The presentation to compress. To customize compression, for example to use a different picture resolution or to skip a step, call the functions listed above individually instead of this one. Cropped areas of pictures are removed permanently and cannot be restored in PowerPoint. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | presentation is null. |


---


### removeUnusedLayoutSlides {#removeUnusedLayoutSlides}

| Name | Description |
| --- | --- |
| removeUnusedLayoutSlides ([Presentation](../presentation)) | Makes compression of the Presentation by removing unused layout slides. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The presentation instance |


---


### removeUnusedMasterSlides {#removeUnusedMasterSlides}

| Name | Description |
| --- | --- |
| removeUnusedMasterSlides ([Presentation](../presentation)) | Makes compression of the Presentation by removing unused master slides. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The presentation instance |


---


