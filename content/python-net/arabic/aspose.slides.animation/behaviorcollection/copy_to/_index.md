---
title: copy_to method
second_title: مرجع API لـ Aspose.Slides for Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
ينسخ عناصر **System.Collections.Generic.ICollection`1** إلى **System.Array**، بدءًا من فهرس **System.Array** معين.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array | **List[IBehavior]** | مصفوفة **System.Array** أحادية البُعد التي هي هدف العناصر المنسوخة من **System.Collections.Generic.ICollection`1**. يجب أن تكون **System.Array** ذات فهرسة تبدأ من الصفر. |
| array_index | **int** | الفهرس الصفري في `array` حيث يبدأ النسخ. |

### استثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` أصغر من 0. |
| **RuntimeError(Proxy error(ArgumentException))** | عدد العناصر في المصدر **System.Collections.Generic.ICollection`1** أكبر من المساحة المتاحة من `array_index` إلى نهاية `array` الوجهة. |



### انظر أيضًا
* الفئة [`BehaviorCollection`](/slides/python-net/ar/aspose.slides.animation/behaviorcollection)
* الوحدة [`aspose.slides.animation`](/slides/python-net/ar/aspose.slides.animation)
* المكتبة [`Aspose.Slides`](/slides/python-net)