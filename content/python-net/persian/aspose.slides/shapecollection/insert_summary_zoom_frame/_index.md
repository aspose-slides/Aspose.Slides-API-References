---
title: insert_summary_zoom_frame method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
یک فریم Summary Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص درج می‌نماید.

### بازگشت

[`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe) جدید ایجاد شده.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-مبتنی که فریم Summary Zoom در آن درج می‌شود. |
| x | **float** | مختصات x فریم Summary Zoom جدید، به نقطه. |
| y | **float** | مختصات y فریم Summary Zoom جدید، به نقطه. |
| width | **float** | عرض فریم Summary Zoom جدید، به نقطه. |
| height | **float** | ارتفاع فریم Summary Zoom جدید، به نقطه. |

### توضیحات

این متد یک فریم Summary Zoom ایجاد می‌کند که پیوندهای خلاصه برای تمام بخش‌های ارائه را تجمیع می‌کند.

### استثناها

| استثنا | توضیح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | اگر ارائه هیچ بخشی نداشته باشد، یا اسلاید هدف متعلق به هیچ بخشی نباشد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)