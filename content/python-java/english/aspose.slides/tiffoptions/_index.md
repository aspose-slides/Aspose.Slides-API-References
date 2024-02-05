---
title: TiffOptions
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/tiffoptions/
---

## TiffOptions class

 Provides options that control how a presentation is saved in TIFF format.
 
### TiffOptions {#TiffOptions}

| Name | Description |
| --- | --- |
| TiffOptions() | Default constructor. |

 **Result:**
TiffOptions


---


### getCompressionType {#getCompressionType}

| Name | Description |
| --- | --- |
| getCompressionType() | Specifies the compression type. Read/write TiffCompressionTypes. |

 **Result:**
int


---


### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont() | Returns or sets font used in case source font is not found. Read-write String. |

 **Result:**
String


---


### getDpiX {#getDpiX}

| Name | Description |
| --- | --- |
| getDpiX() | Specifies the horizontal resolution in dots per inch. Read/write long. |

 **Result:**
long


---


### getDpiY {#getDpiY}

| Name | Description |
| --- | --- |
| getDpiY() | Specifies the vertical resolution in dots per inch. Read/write long. |

 **Result:**
long


---


### getImageSize {#getImageSize}

| Name | Description |
| --- | --- |
| getImageSize() | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension. |

 **Result:**
Dimension


---


### getNotesCommentsLayouting {#getNotesCommentsLayouting}

| Name | Description |
| --- | --- |
| getNotesCommentsLayouting() | Provides options that control how notes and comments is placed in exported document. |

 **Result:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)


---


### getPixelFormat {#getPixelFormat}

| Name | Description |
| --- | --- |
| getPixelFormat() | Specifies the pixel format for the generated images. Read/write ImagePixelFormat. |

 **Result:**
int


---


### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback() | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Result:**
IProgressCallback


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides() | Specifies whether the generated document should include hidden slides or not. Default is false. |

 **Result:**
boolean


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback() | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Result:**
IWarningCallback


---


### setCompressionType {#setCompressionType}

| Name | Description |
| --- | --- |
| setCompressionType(int) | Specifies the compression type. Read/write TiffCompressionTypes. |


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont(String) | Returns or sets font used in case source font is not found. Read-write String. |


---


### setDpiX {#setDpiX}

| Name | Description |
| --- | --- |
| setDpiX(long) | Specifies the horizontal resolution in dots per inch. Read/write long. |


---


### setDpiY {#setDpiY}

| Name | Description |
| --- | --- |
| setDpiY(long) | Specifies the vertical resolution in dots per inch. Read/write long. |


---


### setImageSize {#setImageSize}

| Name | Description |
| --- | --- |
| setImageSize(Dimension) | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension. |


---


### setPixelFormat {#setPixelFormat}

| Name | Description |
| --- | --- |
| setPixelFormat(int) | Specifies the pixel format for the generated images. Read/write ImagePixelFormat. |


---


### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback([IProgressCallback](../iprogresscallback)) | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides(boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback([IWarningCallback](../iwarningcallback)) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


