---
title: SvgImage
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/svgimage/
---

## SvgImage class

 Represents an SVG image.
 
### SvgImage {#SvgImage}

| Name | Description |
| --- | --- |
| SvgImage(byte[]) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |

 **Returns:**
SvgImage


---


### SvgImage {#SvgImage}

| Name | Description |
| --- | --- |
| SvgImage(String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |

 **Returns:**
SvgImage


---


### createSvgImageFromBytes  {#createSvgImageFromBytes }

| Name | Description |
| --- | --- |
| createSvgImageFromBytes (Bytes[]) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | Bytes[] | Svg stream. |

 **Returns:**
SvgImage


---


### SvgImage {#SvgImage}

| Name | Description |
| --- | --- |
| SvgImage(byte[], [HtmlExternalResolver](../htmlexternalresolver), String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Returns:**
SvgImage


---


### SvgImage {#SvgImage}

| Name | Description |
| --- | --- |
| SvgImage(byte[], [ExternalResourceResolver](../externalresourceresolver), String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Returns:**
SvgImage


---


### SvgImage {#SvgImage}

| Name | Description |
| --- | --- |
| SvgImage(String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Returns:**
SvgImage


---


### SvgImage {#SvgImage}

| Name | Description |
| --- | --- |
| SvgImage(String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Returns:**
SvgImage


---


### createSvgImageFromBytes  {#createSvgImageFromBytes }

| Name | Description |
| --- | --- |
| createSvgImageFromBytes (Bytes[], [HtmlExternalResolver](../htmlexternalresolver), String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | Bytes[] | Svg stream. |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Returns:**
SvgImage


---


### createSvgImageFromBytes  {#createSvgImageFromBytes }

| Name | Description |
| --- | --- |
| createSvgImageFromBytes (Bytes[], [ExternalResourceResolver](../externalresourceresolver), String) | Creates new SvgImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | Bytes[] | Svg stream. |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Returns:**
SvgImage


---


### getBaseUri {#getBaseUri}

| Name | Description |
| --- | --- |
| getBaseUri() | Returns base URI of the specified Svg. Used to resolve relative links. Read-only String. |

 **Returns:**
String


---


### getExternalResourceResolver {#getExternalResourceResolver}

| Name | Description |
| --- | --- |
| getExternalResourceResolver() | Return callback interface used to resolve external resources during Svg documents import. Read-only IExternalResourceResolver. |

 **Returns:**
[HtmlExternalResolver](../htmlexternalresolver), [ExternalResourceResolver](../externalresourceresolver)


---


### getSvgContent {#getSvgContent}

| Name | Description |
| --- | --- |
| getSvgContent() | Returns SVG content. Read-only String. |

 **Returns:**
String


---


### getSvgData {#getSvgData}

| Name | Description |
| --- | --- |
| getSvgData() | Returns SVG data. Read-only byte[]. |

 **Returns:**
byte


---


