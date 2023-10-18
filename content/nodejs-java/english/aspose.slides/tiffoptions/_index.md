---
title: TiffOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/tiffoptions/
---

## TiffOptions class

 Provides options that control how a presentation is saved in TIFF format.
 
### TiffOptions {#TiffOptions}

| Name | Description |
| --- | --- |
| TiffOptions() | Default function. |

 **Result:**
TiffOptions


---


### getBwConversionMode {#getBwConversionMode}

| Name | Description |
| --- | --- |
| getBwConversionMode () | Specifies the algorithm for converting a color image into a black and white image. This option will applied only if CompressionType( #getCompressionType/ #setCompressionType(int)) is set to TiffCompressionTypes#CCITT4 or TiffCompressionTypes#CCITT3 Read/write BlackWhiteConversionMode. Default is BlackWhiteConversionMode#Default. |

 **Result:**
int


---


### getCompressionType {#getCompressionType}

| Name | Description |
| --- | --- |
| getCompressionType () | Specifies the compression type. Read/write TiffCompressionTypes. |

 **Result:**
int


---


### getDpiX {#getDpiX}

| Name | Description |
| --- | --- |
| getDpiX () | Specifies the horizontal resolution in dots per inch. Read/write long. |

 **Result:**
long


---


### getDpiY {#getDpiY}

| Name | Description |
| --- | --- |
| getDpiY () | Specifies the vertical resolution in dots per inch. Read/write long. |

 **Result:**
long


---


### getImageSize {#getImageSize}

| Name | Description |
| --- | --- |
| getImageSize () | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension. |

 **Result:**
Dimension


---


### getNotesCommentsLayouting {#getNotesCommentsLayouting}

| Name | Description |
| --- | --- |
| getNotesCommentsLayouting () | Provides options that control how notes and comments is placed in exported document. |

 **Result:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)


---


### getPixelFormat {#getPixelFormat}

| Name | Description |
| --- | --- |
| getPixelFormat () | Specifies the pixel format for the generated images. Read/write ImagePixelFormat. |

 **Result:**
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Specifies whether the generated document should include hidden slides or not. Default is false. |

 **Result:**
boolean


---


### setBwConversionMode {#setBwConversionMode}

| Name | Description |
| --- | --- |
| setBwConversionMode (int) | Specifies the algorithm for converting a color image into a black and white image. This option will applied only if CompressionType( #getCompressionType/ #setCompressionType(int)) is set to TiffCompressionTypes#CCITT4 or TiffCompressionTypes#CCITT3 Read/write BlackWhiteConversionMode. Default is BlackWhiteConversionMode#Default. |


---


### setCompressionType {#setCompressionType}

| Name | Description |
| --- | --- |
| setCompressionType (int) | Specifies the compression type. Read/write TiffCompressionTypes. |


---


### setDpiX {#setDpiX}

| Name | Description |
| --- | --- |
| setDpiX (long) | Specifies the horizontal resolution in dots per inch. Read/write long. |


---


### setDpiY {#setDpiY}

| Name | Description |
| --- | --- |
| setDpiY (long) | Specifies the vertical resolution in dots per inch. Read/write long. |


---


### setImageSize {#setImageSize}

| Name | Description |
| --- | --- |
| setImageSize (Dimension) | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write java.awt.Dimension. |


---


### setPixelFormat {#setPixelFormat}

| Name | Description |
| --- | --- |
| setPixelFormat (int) | Specifies the pixel format for the generated images. Read/write ImagePixelFormat. |


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


