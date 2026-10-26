---
title: copy_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
عناصر **System.Collections.Generic.ICollection`1** را به یک **System.Array** کپی می‌کند، به‌طوری‌که از یک ایندکس خاص **System.Array** شروع شود.


```python
def copy_to(self, array, array_index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| array | **List[IParagraph]** | آرایهٔ **System.Array** یک‌بعدی که مقصد عناصری است که از **System.Collections.Generic.ICollection`1** کپی شده‌اند. **System.Array** باید دارای ایندکس صفر مبنایی باشد. |
| array_index | **int** | اندیس صفر مبنایی در `array` که از آنجا کپی آغاز می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` برابر None است. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` کمتر از ۰ است. |
| **RuntimeError(Proxy error(ArgumentException))** | تعداد عناصر در **System.Collections.Generic.ICollection`1** منبع بیشتر از فضای موجود از `array_index` تا انتهای `array` مقصد است. |



### موارد مرتبط
* کلاس [`ParagraphCollection`](/slides/python-net/fa/aspose.slides/paragraphcollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)