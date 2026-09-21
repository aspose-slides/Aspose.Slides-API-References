---
title: delete_column method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
ستون مشخص‌شده را حذف می‌کند

```python
def delete_column(self, column_index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| column_index | **int** | شاخص صفر مبنای ستونی که باید حذف شود. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که سعی می‌کنید آخرین ستون تنها در ماتریس را حذف کنید |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اگر columnIndex کمتر از صفر یا بزرگتر یا برابر با ColumnCount باشد |

### موارد مرتبط
* کلاس [`MathMatrix`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)