---
title: SvgImage
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/svgimage/
---
## SvgImage classe

 Représente une image SVG.
 
### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(byte[]) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(InputStream) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Svg stream. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(byte[], [HtmlExternalResolver](../htmlexternalresolver), String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(byte[], [ExternalResourceResolver](../externalresourceresolver), String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| svgContent | String | Svg content. |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Svg stream. |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Renvoie:**
SvgImage


---


### SvgImage {#SvgImage}

| Nom | Description |
| --- | --- |
| SvgImage(InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | Creates new SvgImage object. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Svg stream. |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| baseUri | String | Base URI of the specified Svg. Used to resolve relative links. |

 **Renvoie:**
SvgImage


---


### getBaseUri {#getBaseUri}

| Nom | Description |
| --- | --- |
| getBaseUri () | Returns base URI of the specified Svg. Used to resolve relative links. Lecture seule String. |

 **Renvoie:**
String


---


### getExternalResourceResolver {#getExternalResourceResolver}

| Nom | Description |
| --- | --- |
| getExternalResourceResolver () | Return callback interface used to resolve external resources during Svg documents import. Lecture seule IExternalResourceResolver. |

 **Renvoie:**
[HtmlExternalResolver](../htmlexternalresolver), [ExternalResourceResolver](../externalresourceresolver)


---


### getSvgContent {#getSvgContent}

| Nom | Description |
| --- | --- |
| getSvgContent () | Returns SVG content. Lecture seule String. |

 **Renvoie:**
String


---


### getSvgData {#getSvgData}

| Nom | Description |
| --- | --- |
| getSvgData () | Returns SVG data. Lecture seule byte[]. |

 **Renvoie:**
byte


---


### writeAsEmf {#writeAsEmf}

| Nom | Description |
| --- | --- |
| writeAsEmf (OutputStream) | Saves the SVG image as an EMF file. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Target stream |

 **Renvoie:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentNullException | Le flux cible est null |