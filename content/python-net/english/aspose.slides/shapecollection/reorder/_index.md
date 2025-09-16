---
title: reorder method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/reorder/
weight: 370
---


## reorder {#int-ishape}
Moves the specified shape to a new position within the shape collection.


```python
def reorder(self, index, shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based target index where the shape will be placed. |
| shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | The [`IShape`](/slides/python-net/aspose.slides/ishape) to move within the collection. |


## reorder {#int-listishape}
Moves the specified shapes within the shape collection, placing them starting at the given index.


```python
def reorder(self, index, shapes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based target index where the first specified shape will be placed; <br/><br/>            subsequent shapes follow in the order provided. |
| shapes | **List[IShape]** | One or more [`IShape`](/slides/python-net/aspose.slides/ishape) instances to move within the collection. |



### See Also
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

