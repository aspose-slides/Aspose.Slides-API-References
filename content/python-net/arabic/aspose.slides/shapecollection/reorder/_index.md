---
title: reorder method
second_title: Aspose.Slides لـ بايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
يقوم بنقل shape المحدد إلى موضع جديد داخل مجموعة الأشكال.


```python
def reorder(self, index, shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | الفهرس الهدف صفر-المؤشر حيث سيتم وضع shape. |
| shape | [`IShape`](/slides/python-net/ar/aspose.slides/ishape) | الـ [`IShape`](/slides/python-net/ar/aspose.slides/ishape) لنقله داخل المجموعة. |


## reorder(self, index, shapes) {#int-listishape}
يقوم بنقل shapes المحددة داخل مجموعة الأشكال، مع وضعها بدءًا من الفهرس المحدد.


```python
def reorder(self, index, shapes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | الفهرس الهدف صفر-المؤشر حيث سيتم وضع أول shape محدد؛ <br/><br/>            تتبع الأشكال اللاحقة بالترتيب المحدد. |
| shapes | **List[IShape]** | واحد أو أكثر من مثيلات [`IShape`](/slides/python-net/ar/aspose.slides/ishape) لنقلها داخل المجموعة. |



### انظر أيضا
* فئة [`IShape`](/slides/python-net/ar/aspose.slides/ishape)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)