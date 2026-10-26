---
title: overlap property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## ویژگی overlap
مشخص می‌کند که نوارها و ستون‌ها تا چه اندازه در نمودارهای دو-بعدی همپوشانی دارند، به صورت درصد (از -100% تا 100%). 
            این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است. 
            این یک پیش‌نمایش از ویژگی مناسب در گروه سری والد است و بنابراین این ویژگی فقط-خواندنی است.
            برای تغییر مقدار، از ویژگی read/write ParentSeriesGroup.Overlap استفاده کنید.
            فقط-خواندنی **int**.


### توضیحات

Overlap مشخص می‌کند درجهٔ همپوشانی یا فاصله بین نوارها و ستون‌ها به صورت درصدی از عرض آن‌ها:
            - -100%: حداکثر فاصله (نوارها کاملاً جدا هستند).
            - 0%: نوارها بدون همپوشانی یا فاصله در کنار هم قرار می‌گیرند.
            - 100%: حداکثر همپوشانی (نوارها کاملاً یکدیگر را پوشش می‌دهند).
            این یک پیش‌نمایش از ویژگی ParentSeriesGroup.Overlap است.

### تعریف:
```python
@property
def overlap(self):
    ...
```


### موارد مرتبط
* کلاس [`IChartSeries`](/slides/python-net/fa/aspose.slides.charts/ichartseries)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)