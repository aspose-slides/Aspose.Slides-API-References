---
title: Output
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/output/
---

## Output class

 Represents a collection of output elements for IWebDocument.
 
| [add] ([String], [String], [TContextObject]) | Adds an output element for the context object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | Output path. |
| templateKey | [String] | The key of the template used for context object transformation before output. |
| contextObject | [TContextObject] | Context object. |

### Result
[OutputFile]


---


| [add] ([String], [PPImage]) | Adds an output element for the image. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | Output path. |
| image | [PPImage] | Image to output. |

### Result
[OutputFile]


---


| [add] ([String], [BufferedImage]) | Adds an output element for the image. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | Output path. |
| image | [BufferedImage] | Image to output. |

### Result
[OutputFile]


---


| [add] ([String], [Video]) | Adds an output element for the video. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | Output path. |
| video | [Video] | Video to output. |

### Result
[OutputFile]


---


| [add] ([String], [FontData], [int]) | Adds an output element for the font. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | Output path. |
| fontData | [FontData] | Font to output. |
| fontStyle | [int] | Font style. |

### Result
[OutputFile]


---


| [add] ([String], [String]) | Adds an output element for the text content. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | Output path. |
| textContent | [String] | Content to output. |

### Result
[OutputFile]


---


| [getResourcePath] ([Object]) | Returns the path for a given resource. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| obj | [Object] | Resource object. |

### Result
String


---


