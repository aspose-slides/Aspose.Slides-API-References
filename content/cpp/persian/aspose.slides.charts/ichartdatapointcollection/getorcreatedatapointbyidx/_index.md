---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides برای مرجع API C++
description: "اگر مجموعه قبلاً نقطه داده‌ای با شاخص index داشته باشد، این نقطه داده را برمی‌گرداند. اگر مجموعه نقطه داده‌ای با شاخص index ==N نداشته باشد (زمانی که تعداد نقطه‌های داده در این مجموعه کمتر یا مساوی N باشد)، نقطه‌های داده‌ی کمبود را اضافه کرده و آخرین (که شاخص درخواست‌شده را دارد) را برمی‌گرداند. برای مثال، شاخص‌های مجموعه {0, 1, 2} هستند و شاخص درخواست‌شده 5 است. سپس متد نقطه‌های داده‌ی کمبود را اضافه می‌کند: {0, 1, 2, 3, 4, 5}. و نقطه داده با شاخص 5 را برمی‌گرداند."
type: docs
weight: 131
url: /fa/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) متد

اگر مجموعه قبلاً نقطه داده‌ای با شاخص *index* داشته باشد، این نقطه داده را برمی‌گرداند. اگر مجموعه نقطه داده‌ای با شاخص *index* ==N نداشته باشد (زمانی که تعداد نقطه‌های داده در این مجموعه کمتر یا برابر N باشد) سپس نقطه‌های داده کمبود را اضافه کرده و آخرین نقطه (که شاخص درخواستی را دارد) را برمی‌گرداند. برای مثال، شاخص‌های مجموعه {0, 1, 2} هستند و شاخص درخواستی 5 است. سپس متد نقطه‌های داده کمبود را اضافه می‌کند: {0, 1, 2, 3, 4, 5}. و نقطه داده با شاخص 5 را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **uint32_t** | شاخص. |

### مقدار بازگشت

نقطه داده با شاخص درخواستی را برمی‌گرداند.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataPoint](../../ichartdatapoint/)
* کلاس [IChartDataPointCollection](../)
* فضای نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)