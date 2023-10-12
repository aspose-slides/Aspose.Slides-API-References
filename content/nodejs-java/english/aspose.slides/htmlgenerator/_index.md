---
title: HtmlGenerator
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/htmlgenerator/
---

## HtmlGenerator class

 Html generator.
 
| Name | Description |
| --- | --- |
| addAttributeValue (String) | Quotes attribute value and adds it to the html file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | String | Attribute value string. |


---


| Name | Description |
| --- | --- |
| addAttributeValue (char[]) | Quotes attribute value and adds it to the html file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | char[] | Attribute value string. |


---


| Name | Description |
| --- | --- |
| addAttributeValue (char[], int, int) | Quotes attribute value and adds it to the html file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | char[] | Attribute value string. |
| startIndex | int | Start index of the portion to add. |
| length | int | Length of the portion to add. |


---


| Name | Description |
| --- | --- |
| addHtml (String) | Adds formatted HTML text. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| html | String | Text to add. |


---


| Name | Description |
| --- | --- |
| addHtml (char[]) | Adds formatted HTML text. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| html | char[] | Text to add. |


---


| Name | Description |
| --- | --- |
| addHtml (char[], int, int) | Adds formatted HTML text. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| html | char[] | Text to add. |
| startIndex | int | Start index of the portion to add. |
| length | int | Length of the portion to add. |


---


| Name | Description |
| --- | --- |
| addText (String) | Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text to add. |


---


| Name | Description |
| --- | --- |
| addText (char[]) | Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | char[] | Text to add. |


---


| Name | Description |
| --- | --- |
| addText (char[], int, int) | Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | char[] | Text to add. |
| startIndex | int | Start index of the portion to add. |
| length | int | Length of the portion to add. |


---


| Name | Description |
| --- | --- |
| getNextSlideIndex () | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getPreviousSlideIndex () | Returns index of previously rendered slide or -1 if first slide is rendering. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getSlideImageSize () | Returns slide image size. Read-only java.awt.geom.Dimension2D. |

### Result
Dimension2D


---


| Name | Description |
| --- | --- |
| getSlideImageSizeUnit () | Returns a unit in which slide image size is specified. Read-only SvgCoordinateUnit. |

### Result
int


---


| Name | Description |
| --- | --- |
| getSlideImageSizeUnitCode () | Returns a css code of unit in which slide image size is specified. Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getSlideIndex () | Returns index of currently rendering slide. Read-only int. |

### Result
int


---


