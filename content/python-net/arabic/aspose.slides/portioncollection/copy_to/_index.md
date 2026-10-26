---
title: copy_to method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
ينسخ عناصر **System.Collections.Generic.ICollection`1** إلى **System.Array**، بدءًا من فهرس **System.Array** معين.

```python
def copy_to(self, array, array_index):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| array | **List[IPortion]** | المصفوفة أحادية البعد **System.Array** التي هي وجهة العناصر المنقولة من **System.Collections.Generic.ICollection`1**. يجب أن يكون لـ **System.Array** فهرسة تبدأ من الصفر. |
| array_index | **int** | الفهرس صفر-الأساس في `array` الذي يبدأ النسخ عنده. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` أصغر من 0. |
| **RuntimeError(Proxy error(ArgumentException))** | عدد العناصر في المصدر **System.Collections.Generic.ICollection`1** أكبر من المسافة المتاحة من `array_index` إلى نهاية `array` الوجهة. |

### انظر أيضًا
* فئة [`PortionCollection`](/slides/python-net/ar/aspose.slides/portioncollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)