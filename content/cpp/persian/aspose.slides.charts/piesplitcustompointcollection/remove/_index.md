---
title: Remove()
second_title: Aspose.Slides برای مرجع API C++
description: مورد را از مجموعه حذف می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) متد


مورد را از مجموعه حذف می‌کند.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | نقطه داده برای حذف. |

### مقدار بازگشتی

true اگر مورد با موفقیت حذف شود؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر مورد در [System::Collections::Generic::List](../../../system.collections.generic/list/){T} یافت نشود.

## PieSplitCustomPointCollection::Remove(int32_t) متد


مورد را از مجموعه با استفاده از شاخص آن در مجموعه نقاط سری والد حذف می‌کند.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPointIndex | **int32_t** | شاخص نقطه داده در مجموعه نقاط سری والد. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataPoint](../../ichartdatapoint/)
* کلاس [PieSplitCustomPointCollection](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)