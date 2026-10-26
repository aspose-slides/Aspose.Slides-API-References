---
title: add_summary_zoom_frame method
second_title: Aspose.Slides برای Python از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
یک فریم Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌سالید.

### بازگشت

[`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe) تازه ایجاد شده.

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x فریم Summary Zoom جدید، به نقطه. |
| y | **float** | مختصات y فریم Summary Zoom جدید، به نقطه. |
| width | **float** | عرض فریم Summary Zoom جدید، به نقطه. |
| height | **float** | ارتفاع فریم Summary Zoom جدید، به نقطه. |

### توضیحات

این متد یک فریم Summary Zoom ایجاد می‌کند که پیوندهای خلاصه را برای تمام بخش‌های ارائه تجمیع می‌کند.

### استثناها

| استثنا | توضیح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | اگر در ارائه هیچ بخشی وجود نداشته باشد یا اسلاید هدف به هیچ بخشی تعلق نداشته باشد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* کلاس [`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)