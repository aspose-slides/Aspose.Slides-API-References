---
title: MarkdownSaveOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/markdownsaveoptions/
---

## MarkdownSaveOptions class

 Represents options that control how presentation should be saved to markdown.
 
### MarkdownSaveOptions {#MarkdownSaveOptions}

| Name | Description |
| --- | --- |
| MarkdownSaveOptions() | Ctor. |

 **Returns:**
MarkdownSaveOptions


---


### getBasePath {#getBasePath}

| Name | Description |
| --- | --- |
| getBasePath () | Specifies the base path where document with resources will be saved. Default is the current directory of the application. |

 **Returns:**
String


---


### getExportType {#getExportType}

| Name | Description |
| --- | --- |
| getExportType () | Specifies markdown specification to convert presentation. Default is TextOnly. |

 **Returns:**
int


---


### getFlavor {#getFlavor}

| Name | Description |
| --- | --- |
| getFlavor () | Specifies markdown specification to convert presentation. Default is Multi-markdown. |

 **Returns:**
int


---


### getHandleRepeatedSpaces {#getHandleRepeatedSpaces}

| Name | Description |
| --- | --- |
| getHandleRepeatedSpaces () | Specifies how repeated regular space characters should be handled during Markdown export. This property defines whether consecutive spaces are: - preserved as regular space characters, - alternated between regular spaces and non-breaking space entities (&nbsp;), - or fully replaced (after the first) with a non-breaking space to preserve visual alignment in Markdown output. The default value is HandleRepeatedSpaces#AlternateSpacesToNbsp. |

 **Returns:**
int


---


### getImagesSaveFolderName {#getImagesSaveFolderName}

| Name | Description |
| --- | --- |
| getImagesSaveFolderName () | Specifies folder name to save images. Default is Images. |

 **Returns:**
String


---


### getNewLineType {#getNewLineType}

| Name | Description |
| --- | --- |
| getNewLineType () | Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows). Default is Unix. |

 **Returns:**
int


---


### getRemoveEmptyLines {#getRemoveEmptyLines}

| Name | Description |
| --- | --- |
| getRemoveEmptyLines () | If set to true, removes empty or whitespace-only lines from the final Markdown output. Default is false. |

 **Returns:**
boolean


---


### getShowComments {#getShowComments}

| Name | Description |
| --- | --- |
| getShowComments () | Specifies whether the generated document should show comments or not. Default is false. |

 **Returns:**
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Specifies whether the generated document should include hidden slides or not. Default is false. |

 **Returns:**
boolean


---


### getShowSlideNumber {#getShowSlideNumber}

| Name | Description |
| --- | --- |
| getShowSlideNumber () | Specifies whether the generated document should show number of each slide or not. Default is false. |

 **Returns:**
boolean


---


### getSlideNumberFormat {#getSlideNumberFormat}

| Name | Description |
| --- | --- |
| getSlideNumberFormat () | Gets or sets the format string used for slide number headers in Markdown output. The format must include the "{0}" placeholder, which will be replaced with the slide index during export. Example: "# Slide {0}" will produce "# Slide 1", "# Slide 2", etc. |

 **Returns:**
String

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the format string does not contain the "{0}" placeholder. |


---


### setBasePath {#setBasePath}

| Name | Description |
| --- | --- |
| setBasePath (String) | Specifies the base path where document with resources will be saved. Default is the current directory of the application. |

 **Returns:**
void


---


### setExportType {#setExportType}

| Name | Description |
| --- | --- |
| setExportType (int) | Specifies markdown specification to convert presentation. Default is TextOnly. |

 **Returns:**
void


---


### setFlavor {#setFlavor}

| Name | Description |
| --- | --- |
| setFlavor (int) | Specifies markdown specification to convert presentation. Default is Multi-markdown. |

 **Returns:**
void


---


### setHandleRepeatedSpaces {#setHandleRepeatedSpaces}

| Name | Description |
| --- | --- |
| setHandleRepeatedSpaces (int) | Specifies how repeated regular space characters should be handled during Markdown export. This property defines whether consecutive spaces are: - preserved as regular space characters, - alternated between regular spaces and non-breaking space entities (&nbsp;), - or fully replaced (after the first) with a non-breaking space to preserve visual alignment in Markdown output. The default value is HandleRepeatedSpaces#AlternateSpacesToNbsp. |

 **Returns:**
void


---


### setImagesSaveFolderName {#setImagesSaveFolderName}

| Name | Description |
| --- | --- |
| setImagesSaveFolderName (String) | Specifies folder name to save images. Default is Images. |

 **Returns:**
void


---


### setNewLineType {#setNewLineType}

| Name | Description |
| --- | --- |
| setNewLineType (int) | Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows). Default is Unix. |

 **Returns:**
void


---


### setRemoveEmptyLines {#setRemoveEmptyLines}

| Name | Description |
| --- | --- |
| setRemoveEmptyLines (boolean) | If set to true, removes empty or whitespace-only lines from the final Markdown output. Default is false. |

 **Returns:**
void


---


### setShowComments {#setShowComments}

| Name | Description |
| --- | --- |
| setShowComments (boolean) | Specifies whether the generated document should show comments or not. Default is false. |

 **Returns:**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |

 **Returns:**
void


---


### setShowSlideNumber {#setShowSlideNumber}

| Name | Description |
| --- | --- |
| setShowSlideNumber (boolean) | Specifies whether the generated document should show number of each slide or not. Default is false. |

 **Returns:**
void


---


### setSlideNumberFormat {#setSlideNumberFormat}

| Name | Description |
| --- | --- |
| setSlideNumberFormat (String) | Gets or sets the format string used for slide number headers in Markdown output. The format must include the "{0}" placeholder, which will be replaced with the slide index during export. Example: "# Slide {0}" will produce "# Slide 1", "# Slide 2", etc. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown if the format string does not contain the "{0}" placeholder. |


---


