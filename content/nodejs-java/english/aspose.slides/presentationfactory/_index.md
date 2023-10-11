---
title: PresentationFactory
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationfactory/
---

## PresentationFactory class

 Allows to create presentation via COM interface
 
| [PresentationFactory]() |  |

### Result
PresentationFactory


---


| [createPresentation] () Creates new presentation. |

### Result
[Presentation]


---


| [createPresentation] ([LoadOptions]) Creates new presentation with additional load options |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [LoadOptions] | Load options |

### Result
[Presentation]


---


| [getInstance] () Presentation factory static instance. Read-only PresentationFactory. |

### Result
PresentationFactory


---


| [getPresentationInfo] ([String]) Creates new PresentationInfo object from file and binds presentation to it. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | Presentation file. |

### Result
[PresentationInfo]


---


| [getPresentationInfoFromStream ] (PresentationFactory, [ReadStream], Function) Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | [ReadStream] | Presentation stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PresentationInfo]


---


| [getPresentationText] ([String], [int]) Retrieves the raw text from the slides |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | Input file |
| mode | [int] | Extraction mode |

### Result
[PresentationText]


---


| [getPresentationTextFromStream ] (PresentationFactory, [ReadStream], [int], Function) Retrieves the raw text from the slides |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | [ReadStream] | Input stream |
| mode | [int] | Extraction mode |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PresentationText]


---


| [getPresentationTextFromStream ] (PresentationFactory, [ReadStream], [int], [LoadOptions],  Function) Retrieves the raw text from the slides |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | [ReadStream] | Input stream |
| mode | [int] | Extraction mode |
| options | [LoadOptions] | Load options |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PresentationText]


---


| [readPresentation] ([byte[]]) Reads an existing presentation from array |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | [byte[]] | Array to read |

### Result
[Presentation]


---


| [readPresentation] ([byte[]], [LoadOptions]) Reads an existing presentation from array with additional load options |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | [byte[]] | Array to read |
| options | [LoadOptions] | Load options |

### Result
[Presentation]


---


| [readPresentationFromStream ] (PresentationFactory, [ReadStream], Function) Reads an existing presentation from stream |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | [ReadStream] | Input stream to read |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Presentation]


---


| [readPresentationFromStream ] (PresentationFactory, [ReadStream], [LoadOptions],  Function) Reads an existing presentation from stream with additional load options |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | [ReadStream] | Input stream to read |
| options | [LoadOptions] | Load options |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Presentation]


---


| [readPresentation] ([String]) Reads an existing presentation from file |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | File name |

### Result
[Presentation]


---


| [readPresentation] ([String], [LoadOptions]) Reads an existing presentation from stream with additional load options |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | File name |
| options | [LoadOptions] | Load options |

### Result
[Presentation]


---


