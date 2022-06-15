---
title: setSize
type: docs
weight: 50
url: /php-java/slidesize/setsize/
---

# setSize(int, int) method

  Sets the type of slide size and scales content using scale type.
  
  

##  Parameters

| name | description |
| --- | --- |
| type | Slide size type. |
| scaleType | Scale type of slide content. Assigning any value except SlideSizeType#Custom will change ( #getSize) accordingly, but will keep ( #getOrientation/ #setOrientation(int)) intact. |


# setSize(float, float, int) method

 Sets the size in points and scales content using scale type.
 

##  Parameters

| name | description |
| --- | --- |
| width | Width. |
| height | Height. |
| scaleType | Scale type of slide content. Assigning any value will reset ( #getType) property to SlideSizeType#Custom and set ( #getOrientation/ #setOrientation(int)). |


