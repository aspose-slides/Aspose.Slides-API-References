---
title: copy_to method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
ينسخ عناصر **System.Collections.Generic.ICollection`1** إلى **System.Array**، بدءًا من فهرس **System.Array** معين.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array | **List[IParagraph]** | مصدّر **System.Array** أحادي البعد الذي هو وجهة العناصر المنقولة من **System.Collections.Generic.ICollection`1**. يجب أن يكون لـ **System.Array** فهرسة تبدأ من الصفر. |
| array_index | **int** | الفهرس الذي يبدأ من الصفر في `array` والذي يبدأ النسخ عنده. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` أصغر من 0. |
| **RuntimeError(Proxy error(ArgumentException))** | عدد العناصر في المصدر **System.Collections.Generic.ICollection`1** أكبر من المساحة المتاحة من `array_index` إلى نهاية `array` الوجهة. |



### See Also
* فئة [`ParagraphCollection`](/slides/python-net/ar/aspose.slides/paragraphcollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)