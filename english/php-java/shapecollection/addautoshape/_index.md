---
title: addAutoShape
type: docs
weight: 50
url: /php-java/shapecollection/addautoshape/
---

# addAutoShape(int, float, float, float, float) method

 Creates a new AutoShape, tunes it from default template and adds it to the end of the collection.
 

##  Parameters

| name | description |
| --- | --- |
| shapeType | The ShapeType of shape. |
| x | The X-coordinate for a left side of shape's frame. |
| y | The Y-coordinate for a top side of shape's frame. |
| width | The width of shape's frame. |
| height | The height of shape's frame. |

##  Returns
Created AutoShape object.


# addAutoShape(int, float, float, float, float, boolean) method

 Creates a new AutoShape and adds it to the end of the collection.
 

##  Parameters

| name | description |
| --- | --- |
| shapeType | The ShapeType of shape. |
| x | The X-coordinate for a left side of shape's frame. |
| y | The Y-coordinate for a top side of shape's frame. |
| width | The width of shape's frame. |
| height | The height of shape's frame. |
| createFromTemplate | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

##  Returns
Created AutoShape object.


