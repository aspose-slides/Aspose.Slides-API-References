---
title: SlideSize
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidesize/
---

## SlideSize class

 Represents a size of slide.
 
### getOrientation {#getOrientation}

| Name | Description |
| --- | --- |
| getOrientation () | Returns or sets the slide orientation. Read/write SlideOrientation. Changing this value will swap slide's dimensions. |

 **Result**
int


---


### getSize {#getSize}

| Name | Description |
| --- | --- |
| getSize () | Returns or sets the size in points. Read/write java.awt.geom.Dimension2D. Assigning any value will reset ( #getType) property to SlideSizeType#Custom and set ( #getOrientation/ #setOrientation(int)). |

 **Result**
Dimension2D


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Returns or sets the type of slide size. Read/write SlideSizeType. Assigning any value except SlideSizeType#Custom will change ( #getSize) accordingly, but will keep ( #getOrientation/ #setOrientation(int)) intact. |

 **Result**
int


---


### setOrientation {#setOrientation}

| Name | Description |
| --- | --- |
| setOrientation (int) | Returns or sets the slide orientation. Read/write SlideOrientation. Changing this value will swap slide's dimensions. |


---


### setSize {#setSize}

| Name | Description |
| --- | --- |
| setSize (int, int) | Sets the type of slide size and scales content using scale type. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Slide size type. |
| scaleType | int | Scale type of slide content. Assigning any value except SlideSizeType#Custom will change ( #getSize) accordingly, but will keep ( #getOrientation/ #setOrientation(int)) intact. |


---


### setSize {#setSize}

| Name | Description |
| --- | --- |
| setSize (float, float, int) | Sets the size in points and scales content using scale type. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| width | float | Width. |
| height | float | Height. |
| scaleType | int | Scale type of slide content. Assigning any value will reset ( #getType) property to SlideSizeType#Custom and set ( #getOrientation/ #setOrientation(int)). |


---


