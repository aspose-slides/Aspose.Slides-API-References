---
title: delete_column method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
يحذف العمود المحدد

```python
def delete_column(self, column_index):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| column_index | **int** | الفهرس الصفري للعمود المراد حذفه. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | عندما تحاول حذف العمود الأخير المفرد في المصفوفة |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | إذا كان columnIndex أصغر من الصفر أو أكبر أو يساوي ColumnCount |

### انظر أيضًا
* الفئة [`MathMatrix`](/slides/python-net/ar/aspose.slides.mathtext/mathmatrix)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)