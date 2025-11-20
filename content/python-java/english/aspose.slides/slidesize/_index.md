---
title: SlideSize
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/slidesize/
---

## SlideSize class

 Represents the size and orientation of a slide.
 
### getOrientation {#getOrientation}

| Name | Description |
| --- | --- |
| getOrientation() | Gets or sets the slide orientation. Changing this value swaps the slide&#39s width and height. |

 **Returns:**
int


---


### getSize {#getSize}

| Name | Description |
| --- | --- |
| getSize() | Gets the slide dimensions in points. Assigning a new value resets the #getType property to SlideSizeType#Custom and sets the #getOrientation/ #setOrientation(int). |

 **Returns:**
Dimension2D


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType() | Gets the slide size type. Assigning any value other than SlideSizeType#Custom adjusts the #getSize according to the predefined dimensions, while retaining the current #getOrientation/ #setOrientation(int). |

 **Returns:**
int


---


### setOrientation {#setOrientation}

| Name | Description |
| --- | --- |
| setOrientation(int) | Gets or sets the slide orientation. Changing this value swaps the slide&#39s width and height. |


---


### setSize {#setSize}

| Name | Description |
| --- | --- |
| setSize(int, int) | Sets the slide size by type and scales existing content. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | The predefined slide size to apply. |
| scaleType | int | The content scaling mode to use. Assigning any value other than SlideSizeType#Custom adjusts the #getSize based on the selected type, while preserving #getOrientation/ #setOrientation(int). |


---


### setSize {#setSize}

| Name | Description |
| --- | --- |
| setSize(float, float, int) | Sets the slide dimensions explicitly and scales existing content. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| width | float | The new slide width, in points. |
| height | float | The new slide height, in points. |
| scaleType | int | The content scaling mode to use. This resets the #getType property to SlideSizeType#Custom and sets the #getOrientation/ #setOrientation(int). |


---


