---
title: insertAutoShape
type: docs
weight: 390
url: /php-java/shapecollection/insertautoshape/
---

# insertAutoShape(int, int, float, float, float, float) method

 Creates a new AutoShape, tunes it from default template and inserts it to 
 the collection at the specified index.
 Note: the type of the shape will be determined by the shapeType parameter.
 

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index at which value should be inserted. |
| shapeType | An ShapeType of shape. |
| x | The X-coordinate for a left side of shape's frame. |
| y | The Y-coordinate for a top side of shape's frame. |
| width | The width of shape's frame. |
| height | The height of shape's frame. |

##  Returns
Created AutoShape object.


# insertAutoShape(int, int, float, float, float, float, boolean) method

 Creates a new AutoShape and inserts it to the collection at the specified index.
 Note: the type of the shape will be determined by the shapeType parameter.
 

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index at which value should be inserted. |
| shapeType | An ShapeType of shape. |
| x | The X-coordinate for a left side of shape's frame. |
| y | The Y-coordinate for a top side of shape's frame. |
| width | The width of shape's frame. |
| height | The height of shape's frame. |
| createFromTemplate | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

##  Returns
Created AutoShape object.

