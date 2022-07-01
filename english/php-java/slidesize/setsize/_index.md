---
title: setSize
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/slidesize/setsize/
---

## setSize(int type, int scaleType)  method

  Sets the type of slide size and scales content using scale type.
  
  

### Parameters

| Name | Description |
| --- | --- |
| type | Slide size type. |
| scaleType | Scale type of slide content. Assigning any value except SlideSizeType#Custom will change ( #getSize) accordingly, but will keep ( #getOrientation/ #setOrientation(int)) intact. |


---


## setSize(float width, float height, int scaleType)  method

 Sets the size in points and scales content using scale type.
 

### Parameters

| Name | Description |
| --- | --- |
| width | Width. |
| height | Height. |
| scaleType | Scale type of slide content. Assigning any value will reset ( #getType) property to SlideSizeType#Custom and set ( #getOrientation/ #setOrientation(int)). |


---


