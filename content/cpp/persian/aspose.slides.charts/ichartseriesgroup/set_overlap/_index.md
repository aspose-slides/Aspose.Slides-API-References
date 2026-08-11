---
title: set_Overlap()
second_title: Aspose.Slides برای مرجع API C++
description: مشخص می‌کند نوارها و ستون‌ها در نمودارهای دو-بعدی به چه میزان (به درصد، از -100% تا 100%) همپوشانی داشته باشند.
type: docs
weight: 196
url: /fa/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) متد

مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو-بعدی تا چه میزان (به درصد، از -100% تا 100%) همپوشانی داشته باشند.

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## توضیحات

* -100%: حداکثر فاصله (نوارها کاملاً جدا هستند).
* 0%: نوارها به صورت کنار هم بدون همپوشانی یا فاصله قرار می‌گیرند.
* 100%: حداکثر همپوشانی (نوارها به طور کامل یکدیگر را می‌پوشانند). این ویژگی خواندنی/نوشتنی **int8_t** است.

مثال زیر نشان می‌دهد چگونه همپوشانی را برای یک گروه سری‌نمودار تنظیم کرده و نمودار حاصل را روی یک فرم رندر کنید:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // همپوشانی را به 55% تنظیم کنید

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## موارد مرتبط

* کلاس [IChartSeriesGroup](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)