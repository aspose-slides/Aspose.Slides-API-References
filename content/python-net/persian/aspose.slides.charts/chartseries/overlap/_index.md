---
title: overlap property
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## Overlap ویژگی
مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو-بعدی تا چه میزان هم‌پوشانی دارند، به‌صورت درصد (از -100% تا 100%). 
این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است. 
این یک انتشار از ویژگی مناسب در گروه سری والد است و بنابراین این ویژگی فقط-خواندنی است.
برای تغییر مقدار، از ویژگی **ParentSeriesGroup.Overlap** خواندنی/نوشتنی استفاده کنید.
فقط-خواندنی **int**.

### توضیحات

Overlap درجهٔ هم‌پوشانی یا فاصله بین نوارها و ستون‌ها را به‌عنوان درصدی از عرض آن‌ها مشخص می‌کند:
- -100%: حداکثر فاصله (نوارها به‌طور کامل جدا هستند).
- 0%: نوارها به‌صورت کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند.
- 100%: حداکثر هم‌پوشانی (نوارها به‌طور کامل یکدیگر را پوشش می‌دهند).
این یک انتشار از ویژگی **ParentSeriesGroup.Overlap** است.

### تعریف:
```python
@property
def overlap(self):
    ...
```

### موارد مرتبط
* کلاس [`ChartSeries`](/slides/python-net/fa/aspose.slides.charts/chartseries)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)