---
title: HtmlOptions
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/htmloptions/
---

## HtmlOptions class

 Represents a HTML exporting options.
 
### HtmlOptions {#HtmlOptions}

| Name | Description |
| --- | --- |
| HtmlOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | Creates a new HtmlOptions object specifiing callback. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | Callback object which controls saving project. |

 **Returns:**
HtmlOptions


---


### HtmlOptions {#HtmlOptions}

| Name | Description |
| --- | --- |
| HtmlOptions() | Creates a new HtmlOptions object for saving into single HTML file. |

 **Returns:**
HtmlOptions


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| getDeletePicturesCroppedAreas() | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

 **Returns:**
boolean


---


### getHtmlFormatter {#getHtmlFormatter}

| Name | Description |
| --- | --- |
| getHtmlFormatter() | Returns or sets HTML template. Read/write IHtmlFormatter. |

 **Returns:**
[HtmlFormatter](../htmlformatter)


---


### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions() | Provides options that control the look of Ink objects in exported document. Read-only IInkOptions |

 **Returns:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality() | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |

 **Returns:**
byte


---


### getNotesCommentsLayouting {#getNotesCommentsLayouting}

| Name | Description |
| --- | --- |
| getNotesCommentsLayouting() | Provides options that control how notes and comments is placed in exported document. |

 **Returns:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)


---


### getPicturesCompression {#getPicturesCompression}

| Name | Description |
| --- | --- |
| getPicturesCompression() | Represents the pictures compression level |

 **Returns:**
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides() | Specifies whether the generated document should include hidden slides or not. Default is false. |

 **Returns:**
boolean


---


### getSlideImageFormat {#getSlideImageFormat}

| Name | Description |
| --- | --- |
| getSlideImageFormat() | Returns or sets slide image format options. Read/write ISlideImageFormat. |

 **Returns:**
[SlideImageFormat](../slideimageformat)


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| getSlidesLayoutOptions() | Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions. |

 **Returns:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### getSvgResponsiveLayout {#getSvgResponsiveLayout}

| Name | Description |
| --- | --- |
| getSvgResponsiveLayout() | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |

 **Returns:**
boolean


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| Name | Description |
| --- | --- |
| setDeletePicturesCroppedAreas(boolean) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |


---


### setHtmlFormatter {#setHtmlFormatter}

| Name | Description |
| --- | --- |
| setHtmlFormatter([HtmlFormatter](../htmlformatter)) | Returns or sets HTML template. Read/write IHtmlFormatter. |


---


### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality(byte) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |


---


### setPicturesCompression {#setPicturesCompression}

| Name | Description |
| --- | --- |
| setPicturesCompression(int) | Represents the pictures compression level |


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides(boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


### setSlideImageFormat {#setSlideImageFormat}

| Name | Description |
| --- | --- |
| setSlideImageFormat([SlideImageFormat](../slideimageformat)) | Returns or sets slide image format options. Read/write ISlideImageFormat. |


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions. |


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions. |


---


### setSvgResponsiveLayout {#setSvgResponsiveLayout}

| Name | Description |
| --- | --- |
| setSvgResponsiveLayout(boolean) | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |


---


