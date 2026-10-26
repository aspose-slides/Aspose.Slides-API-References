---
title: insert_summary_zoom_frame method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
یک فریم Summary Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده درج می‌نماید.

### بازگشت

[`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe) جدیداً ایجاد شده.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| پارامتر | نوع | شرح |
| :- | :- | :- |
| index | **int** | اندیس صفر-مبنا که فریم Summary Zoom در آن درج می‌شود. |
| x | **float** | مختصات x فریم Summary Zoom جدید، به پوینت. |
| y | **float** | مختصات y فریم Summary Zoom جدید، به پوینت. |
| width | **float** | عرض فریم Summary Zoom جدید، به پوینت. |
| height | **float** | ارتفاع فریم Summary Zoom جدید، به پوینت. |

### نکات

این روش یک فریم Summary Zoom ایجاد می‌کند که پیوندهای خلاصه را برای تمام بخش‌های ارائه تجمیع می‌کند.

### استثناها

| استثنا | شرح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که ارائه هیچ بخشی نداشته باشد یا اسلاید هدف به هیچ بخشی تعلق نداشته باشد، این استثنا پرتاب می‌شود. |

### همچنین ببینید
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* کلاس [`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)