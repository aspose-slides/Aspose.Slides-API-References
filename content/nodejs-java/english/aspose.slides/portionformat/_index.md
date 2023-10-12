---
title: PortionFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/portionformat/
---

## PortionFormat class

 This class contains the text portion formatting properties. Unlike  IPortionFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  PortionFormat#getEffective method 
 which returns a  IPortionFormatEffectiveData instance.
### PortionFormat {#PortionFormat}

| Name | Description |
| --- | --- |
| PortionFormat() | Initializes a new instance of PortionFormat class. |

 **Result:**
PortionFormat


---


### getBookmarkId {#getBookmarkId}

| Name | Description |
| --- | --- |
| getBookmarkId () | Returns or sets bookmark identifier. Read/write String. |

 **Result:**
String


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective portion formatting data with the inheritance applied. |

 **Result:**
PortionFormatEffectiveData


---


### getHyperlinkClick {#getHyperlinkClick}

| Name | Description |
| --- | --- |
| getHyperlinkClick () | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |

 **Result:**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| Name | Description |
| --- | --- |
| getHyperlinkManager () | Hyperlinks manager. Read-only IHyperlinkManager. |

 **Result:**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| getHyperlinkMouseOver () | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |

 **Result:**
[Hyperlink](../hyperlink)


---


### getSmartTagClean {#getSmartTagClean}

| Name | Description |
| --- | --- |
| getSmartTagClean () | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean. |

 **Result:**
boolean


---


### setBookmarkId {#setBookmarkId}

| Name | Description |
| --- | --- |
| setBookmarkId (String) | Returns or sets bookmark identifier. Read/write String. |


---


### setHyperlinkClick {#setHyperlinkClick}

| Name | Description |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |


---


### setSmartTagClean {#setSmartTagClean}

| Name | Description |
| --- | --- |
| setSmartTagClean (boolean) | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean. |


---


