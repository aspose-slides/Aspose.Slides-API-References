---
title: SvgImage
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/svgimage/
---

## SvgImage class

 Represents an SVG image.
 
| Name | Description |
| --- | --- |
| SvgImage(byte[]) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| SvgImage(String) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| createSvgImageFromStream (ReadStream, Function) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Svg stream. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the SvgImage |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| SvgImage(byte[], ExternalResourceResolver(../externalresourceresolver), String) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | ExternalResourceResolver(../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| SvgImage(byte[], HtmlExternalResolver(../htmlexternalresolver), String) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | HtmlExternalResolver(../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| SvgImage(String, ExternalResourceResolver(../externalresourceresolver), String) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |
| externalResResolver | ExternalResourceResolver(../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| SvgImage(String, HtmlExternalResolver(../htmlexternalresolver), String) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |
| externalResResolver | HtmlExternalResolver(../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| createSvgImageFromStream (ReadStream, ExternalResourceResolver(../externalresourceresolver), String, Function) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Svg stream. |
| externalResResolver | ExternalResourceResolver(../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the SvgImage |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| createSvgImageFromStream (ReadStream, HtmlExternalResolver(../htmlexternalresolver), String, Function) | Creates new SvgImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Svg stream. |
| externalResResolver | HtmlExternalResolver(../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the SvgImage |

### Result
SvgImage


---


| Name | Description |
| --- | --- |
| getBaseUri () | Returns base URI of the specified Svg. Used to resolve relative links. Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getExternalResourceResolver () | Return callback interface used to resolve external resources during Svg documents import. Read-only IExternalResourceResolver. |

### Result
ExternalResourceResolver(../../externalresourceresolver), HtmlExternalResolver(../../htmlexternalresolver)


---


| Name | Description |
| --- | --- |
| getSvgContent () | Returns SVG content. Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getSvgData () | Returns SVG data. Read-only byte[]. |

### Result
byte


---


