---
title: copy_to method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
عناصر **System.Collections.Generic.ICollection`1** را به یک **System.Array** کپی می‌کند، که از یک ایندکس خاص **System.Array** شروع می‌شود.


```python
def copy_to(self, array, array_index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| array | **List[IBehavior]** | **System.Array** یک‌بعدی که مقصد عناصری است که از **System.Collections.Generic.ICollection`1** کپی می‌شوند. **System.Array** باید ایندکس صفر مبنا داشته باشد. |
| array_index | **int** | ایندکس صفر مبنا در `array` که کپی از آن شروع می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` برابر None است. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` کمتر از صفر است. |
| **RuntimeError(Proxy error(ArgumentException))** | تعداد عناصر در منبع **System.Collections.Generic.ICollection`1** بیشتر از فضای موجود از `array_index` تا انتهای `array` مقصد است. |



### مراجع
* کلاس [`BehaviorCollection`](/slides/python-net/fa/aspose.slides.animation/behaviorcollection)
* ماژول [`aspose.slides.animation`](/slides/python-net/fa/aspose.slides.animation)
* کتابخانه [`Aspose.Slides`](/slides/python-net)