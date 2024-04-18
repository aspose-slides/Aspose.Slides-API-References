---
title: PresentationFactory
second_title: Aspose.Sildes for PHP via Java API Reference
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


### getPresentationInfo {#getPresentationInfo}

| Name | Description |
| --- | --- |
| getPresentationInfo (InputStream) | Creates new PresentationInfo object from stream and binds presentation to it. Gets info about presentation in specified stream. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Presentation stream. |

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


### getPresentationText {#getPresentationText}

| Name | Description |
| --- | --- |
| getPresentationText (InputStream, int) | Retrieves the raw text from the slides |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Input stream |
| mode | int | Extraction mode |

 **Returns:**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| Name | Description |
| --- | --- |
| getPresentationText (InputStream, int, [LoadOptions](../loadoptions)) | Retrieves the raw text from the slides |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Input stream |
| mode | int | Extraction mode |
| options | [LoadOptions](../loadoptions) | Load options |

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


### readPresentation {#readPresentation}

| Name | Description |
| --- | --- |
| readPresentation (InputStream) | Reads an existing presentation from stream |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Input stream to read |

 **Returns:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Name | Description |
| --- | --- |
| readPresentation (InputStream, [LoadOptions](../loadoptions)) | Reads an existing presentation from stream with additional load options |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Input stream to read |
| options | [LoadOptions](../loadoptions) | Load options |

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


