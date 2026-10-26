---
title: SaveOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/saveoptions/
---

## SaveOptions class

 Abstract class with options that control how a presentation is saved.
 
### SaveOptions {#SaveOptions}

| Name | Description |
| --- | --- |
| SaveOptions() |  |

 **Returns:**
SaveOptions


---


### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont () | Returns or sets font used in case source font is not found. Read-write String. |

 **Returns:**
String


---


### getGradientStyle {#getGradientStyle}

| Name | Description |
| --- | --- |
| getGradientStyle () | Returns or sets the visual style of the gradient. Read/write GradientStyle. |

 **Returns:**
int


---


### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback () | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Returns:**
IProgressCallback


---


### getSkipJavaScriptLinks {#getSkipJavaScriptLinks}

| Name | Description |
| --- | --- |
| getSkipJavaScriptLinks () | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write boolean. The default value is false. When this property is set to true, hyperlinks with JavaScript calls will be ignored while saving. When this property is set to false, all hyperlinks will be saved. |

 **Returns:**
boolean


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback () | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Returns:**
IWarningCallback


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont (String) | Returns or sets font used in case source font is not found. Read-write String. |

 **Returns:**
void


---


### setGradientStyle {#setGradientStyle}

| Name | Description |
| --- | --- |
| setGradientStyle (int) | Returns or sets the visual style of the gradient. Read/write GradientStyle. |

 **Returns:**
void


---


### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback ([IProgressCallback](../iprogresscallback)) | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Returns:**
void


---


### setSkipJavaScriptLinks {#setSkipJavaScriptLinks}

| Name | Description |
| --- | --- |
| setSkipJavaScriptLinks (boolean) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write boolean. The default value is false. When this property is set to true, hyperlinks with JavaScript calls will be ignored while saving. When this property is set to false, all hyperlinks will be saved. |

 **Returns:**
void


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Returns:**
void


---


