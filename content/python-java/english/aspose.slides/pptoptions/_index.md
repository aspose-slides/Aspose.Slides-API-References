---
title: PptOptions
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/pptoptions/
---

## PptOptions class

 Provides options that control how a presentation is saved in PPT format.
 
### PptOptions {#PptOptions}

| Name | Description |
| --- | --- |
| PptOptions() |  |

 **Result:**
PptOptions


---


### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont () | Returns or sets font used in case source font is not found. Read-write String. |

 **Result:**
String


---


### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback () | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Result:**
IProgressCallback


---


### getRootDirectoryClsid {#getRootDirectoryClsid}

| Name | Description |
| --- | --- |
| getRootDirectoryClsid () | Represents the object class GUID (CLSID) that is stored in the root directory entry. Can be used for COM activation of the document's application. The default value is '64818D11-4F9B-11CF-86EA-00AA00B929E8' that corresponds to 'Microsoft Powerpoint.Slide.8'. |

 **Result:**
UUID


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback () | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Result:**
IWarningCallback


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont (String) | Returns or sets font used in case source font is not found. Read-write String. |


---


### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback ([IProgressCallback](../iprogresscallback)) | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |


---


### setRootDirectoryClsid {#setRootDirectoryClsid}

| Name | Description |
| --- | --- |
| setRootDirectoryClsid (UUID) | Represents the object class GUID (CLSID) that is stored in the root directory entry. Can be used for COM activation of the document's application. The default value is '64818D11-4F9B-11CF-86EA-00AA00B929E8' that corresponds to 'Microsoft Powerpoint.Slide.8'. |


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


