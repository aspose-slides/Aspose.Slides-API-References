---
title: presentation_locking_behavior property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior خاصية
هذه الخاصية تحدد ما إذا كان كائن من الفئة Presentation يمكن أن يكون مالكًا للمصدر - ملف أو تدفق أثناء عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك على تحسين استهلاك الذاكرة والأداء عند العمل مع BLOBs، لكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال عمر كائن Presentation. إليك مثالًا:

### التعريف:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### انظر أيضًا
* فئة [`IBlobManagementOptions`](/slides/python-net/ar/aspose.slides/iblobmanagementoptions)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)