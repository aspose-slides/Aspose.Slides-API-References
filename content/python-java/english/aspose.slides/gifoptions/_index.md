---
title: GifOptions
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/gifoptions/
---

## GifOptions class

 Represents GIF exporting options.
 
### GifOptions {#GifOptions}

| Name | Description |
| --- | --- |
| GifOptions() | Initializes a new instance of the GifOptions class. |

 **Result:**
GifOptions


---


### getDefaultDelay {#getDefaultDelay}

| Name | Description |
| --- | --- |
| getDefaultDelay() | Gets or sets default delay time [ms]. This value will be used if ( ISlideShowTransition#getAdvanceAfterTime/ ISlideShowTransition#setAdvanceAfterTime(long)) is not set. The default value is 1000. |

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


### getExportHiddenSlides {#getExportHiddenSlides}

| Name | Description |
| --- | --- |
| getExportHiddenSlides() | Determines whether hidden slides will be exported. The default value is false. |

 **Result:**
boolean


---


### getFrameSize {#getFrameSize}

| Name | Description |
| --- | --- |
| getFrameSize() | Gets or sets frame size. If the size is empty then the value will be taken from ( IPresentation#getSlideSize) |

 **Result:**
Dimension


---


### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback() | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Result:**
IProgressCallback


---


### getTransitionFps {#getTransitionFps}

| Name | Description |
| --- | --- |
| getTransitionFps() | Gets or sets transition FPS [frames/sec] The default value is 25. |

 **Result:**
int


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback() | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Result:**
IWarningCallback


---


### setDefaultDelay {#setDefaultDelay}

| Name | Description |
| --- | --- |
| setDefaultDelay(int) | Gets or sets default delay time [ms]. This value will be used if ( ISlideShowTransition#getAdvanceAfterTime/ ISlideShowTransition#setAdvanceAfterTime(long)) is not set. The default value is 1000. |


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont(String) | Returns or sets font used in case source font is not found. Read-write String. |


---


### setExportHiddenSlides {#setExportHiddenSlides}

| Name | Description |
| --- | --- |
| setExportHiddenSlides(boolean) | Determines whether hidden slides will be exported. The default value is false. |


---


### setFrameSize {#setFrameSize}

| Name | Description |
| --- | --- |
| setFrameSize(Dimension) | Gets or sets frame size. If the size is empty then the value will be taken from ( IPresentation#getSlideSize) |


---


### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback([IProgressCallback](../iprogresscallback)) | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |


---


### setTransitionFps {#setTransitionFps}

| Name | Description |
| --- | --- |
| setTransitionFps(int) | Gets or sets transition FPS [frames/sec] The default value is 25. |


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback([IWarningCallback](../iwarningcallback)) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


