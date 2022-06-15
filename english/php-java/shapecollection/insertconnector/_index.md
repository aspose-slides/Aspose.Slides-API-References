---
title: insertConnector
type: docs
weight: 460
url: /php-java/shapecollection/insertconnector/
---

# insertConnector(int, int, float, float, float, float) method

 Creates a new Connector, tunes it from default template and inserts it to 
 the collection at the specified index.
 

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
Created Connector object.


# insertConnector(int, int, float, float, float, float, boolean) method

 Creates a new Connector and inserts it to the collection at the specified index.
 

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
Created Connector object.


