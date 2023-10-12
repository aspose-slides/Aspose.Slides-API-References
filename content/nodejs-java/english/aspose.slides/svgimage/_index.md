---
title: SvgImage
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/svgimage/
---

## SvgImage class

 Represents an SVG image.
 
| [SvgImage]([byte[]]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | [byte[]] | Svg data. |

### Result
SvgImage


---


| [SvgImage]([String]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgContent | [String] | Svg content. |

### Result
SvgImage


---


| [createSvgImageFromStream ]([ReadStream], Function) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | [ReadStream] | Svg stream. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the SvgImage |

### Result
SvgImage


---


| [SvgImage]([byte[]], [ExternalResourceResolver], [String]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | [byte[]] | Svg data. |
| externalResResolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [String] | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| [SvgImage]([byte[]], [HtmlExternalResolver], [String]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | [byte[]] | Svg data. |
| externalResResolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [String] | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| [SvgImage]([String], [ExternalResourceResolver], [String]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgContent | [String] | Svg content. |
| externalResResolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [String] | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| [SvgImage]([String], [HtmlExternalResolver], [String]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgContent | [String] | Svg content. |
| externalResResolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [String] | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| [createSvgImageFromStream ]([ReadStream], [ExternalResourceResolver], [String], Function) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | [ReadStream] | Svg stream. |
| externalResResolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [String] | Base URI of the specified Svg. Used to resolve relative links. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the SvgImage |

### Result
SvgImage


---


| [createSvgImageFromStream ]([ReadStream], [HtmlExternalResolver], [String], Function) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | [ReadStream] | Svg stream. |
| externalResResolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | [String] | Base URI of the specified Svg. Used to resolve relative links. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the SvgImage |

### Result
SvgImage


---


| [getBaseUri] () | Returns base URI of the specified Svg. Used to resolve relative links. Read-only String. |

### Result
String


---


| [getExternalResourceResolver] () | Return callback interface used to resolve external resources during Svg documents import. Read-only IExternalResourceResolver. |

### Result
[ExternalResourceResolver], [HtmlExternalResolver]


---


| [getSvgContent] () | Returns SVG content. Read-only String. |

### Result
String


---


| [getSvgData] () | Returns SVG data. Read-only byte[]. |

### Result
byte


---


