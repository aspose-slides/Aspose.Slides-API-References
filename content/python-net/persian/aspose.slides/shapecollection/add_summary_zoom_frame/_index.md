---
title: add_summary_zoom_frame method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
یک فریم جدید Summary Zoom ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

### بازگرداندن

[`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe) جدید ایجاد شده.

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| پارامتر | نوع | شرح |
| :- | :- | :- |
| x | **float** | مختصات x فریم جدید Summary Zoom، بر حسب نقطه. |
| y | **float** | مختصات y فریم جدید Summary Zoom، بر حسب نقطه. |
| width | **float** | عرض فریم جدید Summary Zoom، بر حسب نقطه. |
| height | **float** | ارتفاع فریم جدید Summary Zoom، بر حسب نقطه. |

### توضیحات

این متد یک Summary Zoom جدید ایجاد می‌کند و مجموعه‌ای از اشیاء را برای تمام بخش‌های این ارائه در آن قرار می‌دهد.

### استثناها

| استثنا | شرح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که در ارائه هیچ بخشی وجود نداشته باشد یا اسلاید هدف به هیچ بخشی تعلق نداشته باشد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`ISummaryZoomFrame`](/slides/python-net/fa/aspose.slides/isummaryzoomframe)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)