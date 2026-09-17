---
title: delete_row method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
يحذف الصف المحدد


```python
def delete_row(self, row_index):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| row_index | **int** | الفهرس الصفري للصف المراد حذفه. |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | عندما تحاول حذف الصف الأخير الوحيد في المصفوفة |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | إذا كان rowIndex أقل من الصفر أو أكبر أو يساوي RowCount |

### انظر أيضًا
* فئة [`MathMatrix`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)