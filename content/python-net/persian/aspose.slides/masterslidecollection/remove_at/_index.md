---
title: remove_at method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Removes the element at the specified index of the collection.


```python
def remove_at(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | اندیس صفر مبنا برای عنصر مورد حذف. |

### توضیحات

برای جلوگیری از پرتاب PptxEditException، قبل از آن ویژگی HasDependingSlides مستر را بررسی کنید.

### استثناها

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که مستر مورد حذف در ارائه استفاده شده باشد (ویژگی HasDependingSlides آن صحیح باشد) پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`MasterSlideCollection`](/slides/python-net/fa/aspose.slides/masterslidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)