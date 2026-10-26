---
title: SlideImageFormat
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/slideimageformat/
---

## SlideImageFormat class

 Determines format in which slide image will be saved for presentation to HTML export.
 
### SlideImageFormat {#SlideImageFormat}

| Name | Description |
| --- | --- |
| SlideImageFormat() |  |

 **Returns:**
SlideImageFormat


---


### bitmap {#bitmap}

| Name | Description |
| --- | --- |
| bitmap(float, int) | Slides should be converted to a raster image. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| scale | float | The factor by which to scale the output image. |
| imageFormat | int | The format of the resulting image (e.g., PNG, JPEG). |

 **Returns:**
SlideImageFormat


---


### svg {#svg}

| Name | Description |
| --- | --- |
| svg([SVGOptions](../svgoptions)) | Slides should converted to a SVG format. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [SVGOptions](../svgoptions) | Options for SVG export. |

 **Returns:**
SlideImageFormat


---


