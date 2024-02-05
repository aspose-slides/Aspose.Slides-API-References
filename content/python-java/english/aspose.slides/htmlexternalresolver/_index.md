---
title: HtmlExternalResolver
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/htmlexternalresolver/
---

## HtmlExternalResolver class

 Callback object used by HTML import routine to obtain referrenced objects such as images.
 Using this resolver could create a vulnurability when client provided HTML file will make server software to obtain local or network file. Use with caution. It is recommended not to specify HtmlExternalResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.
### HtmlExternalResolver {#HtmlExternalResolver}

| Name | Description |
| --- | --- |
| HtmlExternalResolver() |  |

 **Result:**
HtmlExternalResolver


---


### getEntity {#getEntity}

| Name | Description |
| --- | --- |
| getEntity (String) | Maps a URI to an object containing the actual resource. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| absoluteUri | String | Absolute URI to the object. |

 **Result:**
InputStream


---


### resolveUri {#resolveUri}

| Name | Description |
| --- | --- |
| resolveUri (String, String) | Resolves the absolute URI from the base and relative URIs. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| baseUri | String | Base URI of linking objects |
| relativeUri | String | Relative URI to the linked object. |

 **Result:**
String


---


