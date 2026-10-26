---
title: PptxOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/pptxoptions/
---

## PptxOptions class

 Represents options for saving OpenXml presentations (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
 
### PptxOptions {#PptxOptions}

| Name | Description |
| --- | --- |
| PptxOptions() | Creates new instance of PptxOptions |

 **Returns:**
PptxOptions


---


### getCompressionLevel {#getCompressionLevel}

| Name | Description |
| --- | --- |
| getCompressionLevel () | Specifies the compression level used when saving the presentation document. The default value is CompressionLevel#Level6. Higher compression levels produce smaller files but require more processing time. The actual compression ratio depends on the content of the presentation. |

 **Returns:**
int


---


### getConformance {#getConformance}

| Name | Description |
| --- | --- |
| getConformance () | Specifies the conformance class to which the Presentation document conforms. Default value is Conformance#Ecma376_2006 |

 **Returns:**
int


---


### getRefreshThumbnail {#getRefreshThumbnail}

| Name | Description |
| --- | --- |
| getRefreshThumbnail () | Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is true. When the option value is true, the new thumbnail will be generated. When the option value is false, the current thumbnail will be saved as is. |

 **Returns:**
boolean


---


### getZip64Mode {#getZip64Mode}

| Name | Description |
| --- | --- |
| getZip64Mode () | Specifies whether the ZIP64 format is used for the Presentation document. The default value is Zip64Mode#IfNecessary |

 **Returns:**
int


---


### setCompressionLevel {#setCompressionLevel}

| Name | Description |
| --- | --- |
| setCompressionLevel (int) | Specifies the compression level used when saving the presentation document. The default value is CompressionLevel#Level6. Higher compression levels produce smaller files but require more processing time. The actual compression ratio depends on the content of the presentation. |

 **Returns:**
void


---


### setConformance {#setConformance}

| Name | Description |
| --- | --- |
| setConformance (int) | Specifies the conformance class to which the Presentation document conforms. Default value is Conformance#Ecma376_2006 |

 **Returns:**
void


---


### setRefreshThumbnail {#setRefreshThumbnail}

| Name | Description |
| --- | --- |
| setRefreshThumbnail (boolean) | Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is true. When the option value is true, the new thumbnail will be generated. When the option value is false, the current thumbnail will be saved as is. |

 **Returns:**
void


---


### setZip64Mode {#setZip64Mode}

| Name | Description |
| --- | --- |
| setZip64Mode (int) | Specifies whether the ZIP64 format is used for the Presentation document. The default value is Zip64Mode#IfNecessary |

 **Returns:**
void


---


