---
title: get_Overlap()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو بعدی تا چه حد (به صورت درصدی از -100% تا 100%) بر روی یکدیگر همپوشانی دارند.
type: docs
weight: 157
url: /fa/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() متد


مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو-بعدی تا چه حد (به‌صورت درصدی از -100% تا 100%) بر روی یکدیگر همپوشانی دارند.

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## توضیحات


* -100%: حداکثر فاصله (نوارها کاملاً جدا هستند).
* 0%: نوارها به صورت کنار هم قرار می‌گیرند بدون همپوشانی یا فاصله.
* 100%: حداکثر همپوشانی (نوارها کاملاً بر روی یکدیگر همپوشانی می‌کنند). این ویژگی قابل‌خواندن/قابل‌نوشتن **int8_t**.



مثال زیر نشان می‌دهد که چگونه همپوشانی برای یک گروه سری نمودار تنظیم شده و نمودار حاصل بر روی فرم رندر می‌شود: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // همپوشانی را برابر 55% تنظیم کنید

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## مراجع مرتبط

* کلاس [ChartSeriesGroup](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)