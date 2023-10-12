---
title: ExternalResourceResolver
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/externalresourceresolver/
---

## ExternalResourceResolver class

 Callback class used to resolve external resources during Html, Svg documents import.
 Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.
###ExternalResourceResolver{#ExternalResourceResolver}

| Name | Description |
| --- | --- |
| ExternalResourceResolver() |  |

 **Result**
ExternalResourceResolver


---


###getEntity{#getEntity}

| Name | Description |
| --- | --- |
| getEntity (String) | Maps a URI to an object containing the actual resource. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| absoluteUri | String | Absolute URI to the object. |

 **Result**
InputStream


---


###resolveUri{#resolveUri}

| Name | Description |
| --- | --- |
| resolveUri (String, String) | Resolves the absolute URI from the base and relative URIs. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| baseUri | String | Base URI of linking objects |
| relativeUri | String | Relative URI to the linked object. |

 **Result**
String


---


