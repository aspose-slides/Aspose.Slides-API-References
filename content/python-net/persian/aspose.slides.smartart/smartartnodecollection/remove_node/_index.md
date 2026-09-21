---
title: remove_node method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
گره یا زیرگره را بر اساس شاخص حذف کنید


```python
def remove_node(self, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر‌پایهٔ گره |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | شاخص کمتر از 0 است.  -or- شاخص برابر یا بزرگتر از تعداد خواهر و برادرها است |


## remove_node(self, node) {#ismartartnode}
گره یا زیرگره را حذف کنید


```python
def remove_node(self, node):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/fa/aspose.slides.smartart/ismartartnode) | گره برای حذف |



### موارد مرتبط
* کلاس [`ISmartArtNode`](/slides/python-net/fa/aspose.slides.smartart/ismartartnode)
* کلاس [`SmartArtNodeCollection`](/slides/python-net/fa/aspose.slides.smartart/smartartnodecollection)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)