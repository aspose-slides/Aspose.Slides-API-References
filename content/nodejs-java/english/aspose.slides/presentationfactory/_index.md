---
title: PresentationFactory
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentationfactory/
---

## PresentationFactory class

 Allows to create presentation via COM interface
 
### PresentationFactory {#PresentationFactory}

| Name | Description |
| --- | --- |
| PresentationFactory() |  |

 **Returns:**
PresentationFactory


---


### createPresentation {#createPresentation}

| Name | Description |
| --- | --- |
| createPresentation () | Creates new presentation. |

 **Returns:**
[Presentation](../presentation)


---


### createPresentation {#createPresentation}

| Name | Description |
| --- | --- |
| createPresentation ([LoadOptions](../loadoptions)) | Creates new presentation with additional load options |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [LoadOptions](../loadoptions) | Load options |

 **Returns:**
[Presentation](../presentation)


---


### getInstance {#getInstance}

| Name | Description |
| --- | --- |
| getInstance () | Presentation factory static instance. Read-only PresentationFactory. |

 **Returns:**
PresentationFactory


---


### getPresentationInfo {#getPresentationInfo}

| Name | Description |
| --- | --- |
| getPresentationInfo (String) | Creates new PresentationInfo object from file and binds presentation to it. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | Presentation file. |

 **Returns:**
[PresentationInfo](../presentationinfo)


---


### getPresentationInfoFromStream  {#getPresentationInfoFromStream }

| Name | Description |
| --- | --- |
| getPresentationInfoFromStream  (PresentationFactory, ReadStream, Function) | Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | ReadStream | Presentation stream. |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[PresentationInfo](../presentationinfo)


---


### getPresentationText {#getPresentationText}

| Name | Description |
| --- | --- |
| getPresentationText (String, int) | Retrieves the raw text from the slides |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file |
| mode | int | Extraction mode |

 **Returns:**
[PresentationText](../presentationtext)


---


### getPresentationTextFromStream  {#getPresentationTextFromStream }

| Name | Description |
| --- | --- |
| getPresentationTextFromStream  (PresentationFactory, ReadStream, int, Function) | Retrieves the raw text from the slides |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | ReadStream | Input stream |
| mode | int | Extraction mode |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[PresentationText](../presentationtext)


---


### getPresentationTextFromStream  {#getPresentationTextFromStream }

| Name | Description |
| --- | --- |
| getPresentationTextFromStream  (PresentationFactory, ReadStream, int, [LoadOptions](../loadoptions),  Function) | Retrieves the raw text from the slides |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | ReadStream | Input stream |
| mode | int | Extraction mode |
| options | [LoadOptions](../loadoptions) | Load options |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[PresentationText](../presentationtext)


---


### readPresentation {#readPresentation}

| Name | Description |
| --- | --- |
| readPresentation (byte[]) | Reads an existing presentation from array |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Array to read |

 **Returns:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Name | Description |
| --- | --- |
| readPresentation (byte[], [LoadOptions](../loadoptions)) | Reads an existing presentation from array with additional load options |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Array to read |
| options | [LoadOptions](../loadoptions) | Load options |

 **Returns:**
[Presentation](../presentation)


---


### readPresentationFromStream  {#readPresentationFromStream }

| Name | Description |
| --- | --- |
| readPresentationFromStream  (PresentationFactory, ReadStream, Function) | Reads an existing presentation from stream |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | ReadStream | Input stream to read |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[Presentation](../presentation)


---


### readPresentationFromStream  {#readPresentationFromStream }

| Name | Description |
| --- | --- |
| readPresentationFromStream  (PresentationFactory, ReadStream, [LoadOptions](../loadoptions),  Function) | Reads an existing presentation from stream with additional load options |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentationfactory | PresentationFactory  | link to self |
| stream | ReadStream | Input stream to read |
| options | [LoadOptions](../loadoptions) | Load options |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |

 **Returns:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Name | Description |
| --- | --- |
| readPresentation (String) | Reads an existing presentation from file |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | File name |

 **Returns:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Name | Description |
| --- | --- |
| readPresentation (String, [LoadOptions](../loadoptions)) | Reads an existing presentation from stream with additional load options |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | File name |
| options | [LoadOptions](../loadoptions) | Load options |

 **Returns:**
[Presentation](../presentation)


---


