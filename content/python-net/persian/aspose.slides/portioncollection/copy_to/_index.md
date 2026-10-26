---
title: copy_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
عناصر **System.Collections.Generic.ICollection`1** را به یک **System.Array** کپی می‌کند، به‌طوری که از یک ایندکس خاص **System.Array** شروع شود.

```python
def copy_to(self, array, array_index):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| array | **List[IPortion]** | آرایهٔ یک‌بعدی **System.Array** که مقصد عناصری است که از **System.Collections.Generic.ICollection`1** کپی می‌شوند. **System.Array** باید ایندکس‌گذاری صفر-پایه داشته باشد. |
| array_index | **int** | ایندکس صفر-پایه در `array` که کپی‌برداری از آنجا آغاز می‌شود. |

### استثنائات

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` برابر None است. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` کمتر از ۰ است. |
| **RuntimeError(Proxy error(ArgumentException))** | تعداد عناصر در منبع **System.Collections.Generic.ICollection`1** بیشتر از فضای موجود از `array_index` تا انتهای `array` مقصد است. |

### موارد مرتبط
* کلاس [`PortionCollection`](/slides/python-net/fa/aspose.slides/portioncollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)