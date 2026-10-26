---
title: add_summary_zoom_section method
second_title: مرجع API Aspose.Slides لـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة

### الإرجاع
تمت إضافة العنصر [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe)

```python
def add_summary_zoom_section(self, section):
    ...
```

| المُعامل | النوع | الوصف |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | القسم لإنشاء عنصر Summary Zoom Section جديد [`ISection`](/slides/python-net/ar/aspose.slides/isection) |

### ملاحظات
إذا كان هناك عنصر لهذا القسم موجود بالفعل في المجموعة، سيتم إرجاع العنصر الموجود.

### استثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | القسم المشار إليه ليس جزءًا من العرض التقديمي الحالي أو لا يحتوي على أي شرائح. |

### انظر أيضًا
* الفئة [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* الفئة [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe)
* الفئة [`ISummaryZoomSection`](/slides/python-net/ar/aspose.slides/isummaryzoomsection)
* الفئة [`SummaryZoomSectionCollection`](/slides/python-net/ar/aspose.slides/summaryzoomsectioncollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)