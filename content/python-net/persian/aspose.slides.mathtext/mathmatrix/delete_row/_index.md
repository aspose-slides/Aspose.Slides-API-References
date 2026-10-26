---
title: delete_row method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
ردیف مشخص‌شده را حذف می‌کند


```python
def delete_row(self, row_index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| row_index | **int** | اندیس صفر-پایه ردیف مورد نظر برای حذف. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | وقتی سعی می‌کنید آخرین ردیف تنها در ماتریس را حذف کنید |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اگر rowIndex کمتر از صفر یا بزرگ‌تر یا مساوی RowCount باشد |



### مراجع دیگر
* کلاس [`MathMatrix`](/slides/python-net/fa/aspose.slides.mathtext/mathmatrix)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)