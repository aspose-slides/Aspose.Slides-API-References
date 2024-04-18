---
title: Output
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/output/
---

## Output class

 Represents a collection of output elements for IWebDocument.
 
### add {#add}

| Name | Description |
| --- | --- |
| add (String, String, TContextObject) | Adds an output element for the context object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| templateKey | String | The key of the template used for context object transformation before output. |
| contextObject | TContextObject | Context object. |

 **Returns:**
[OutputFile](../outputfile)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, [PPImage](../ppimage)) | Adds an output element for the image. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| image | [PPImage](../ppimage) | Image to output. |

 **Returns:**
[OutputFile](../outputfile)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, BufferedImage) | Adds an output element for the image. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| image | BufferedImage | Image to output. |

 **Returns:**
[OutputFile](../outputfile)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, [IImage](../iimage)) | Adds an output element for the image. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| image | [IImage](../iimage) | Image to output. |

 **Returns:**
[OutputFile](../outputfile)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, [Video](../video)) | Adds an output element for the video. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| video | [Video](../video) | Video to output. |

 **Returns:**
[OutputFile](../outputfile)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, [FontData](../fontdata), int) | Adds an output element for the font. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| fontData | [FontData](../fontdata) | Font to output. |
| fontStyle | int | Font style. |

 **Returns:**
[OutputFile](../outputfile)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, String) | Adds an output element for the text content. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | Output path. |
| textContent | String | Content to output. |

 **Returns:**
[OutputFile](../outputfile)


---


### bindResource {#bindResource}

| Name | Description |
| --- | --- |
| bindResource ([OutputFile](../outputfile), Object) | Binds resource to output file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| outputFile | [OutputFile](../outputfile) | Output file. |
| obj | Object | Resource object. |


---


### getResourcePath {#getResourcePath}

| Name | Description |
| --- | --- |
| getResourcePath (Object) | Returns the path for a given resource. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| obj | Object | Resource object. |

 **Returns:**
String


---


