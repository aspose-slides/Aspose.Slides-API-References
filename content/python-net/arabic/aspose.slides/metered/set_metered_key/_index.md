---
title: set_metered_key method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
يضبط المفتاح العام والخاص المتعقب.
            إذا قمت بشراء ترخيص متعقب، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً يكفي ذلك. 
            ومع ذلك، إذا فشل تحميل بيانات الاستهلاك باستمرار وتجاوز 24 ساعة، سيتحول الترخيص إلى حالة التقييم، 
            لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| public_key | **str** | المفتاح العام |
| private_key | **str** | المفتاح الخاص |

### انظر أيضًا
* فئة [`Metered`](/slides/python-net/ar/aspose.slides/metered)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)