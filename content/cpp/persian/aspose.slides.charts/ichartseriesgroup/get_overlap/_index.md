---
title: get_Overlap()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که نوارها و ستون‌ها تا چه حد در نمودارهای 2-بعدی هم‌پوشانی داشته باشند، به‌صورت درصد (از -100% تا 100%).
type: docs
weight: 183
url: /fa/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() متد

مشخص می‌کند که نوارها و ستون‌ها تا چه حد در نمودارهای 2-بعدی هم‌پوشانی داشته باشند، به‌صورت درصد (از -100% تا 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## ملاحظات

* -100%: حداکثر فاصله (نوارها کاملاً جدا هستند).
* 0%: نوارها به‌صورت کنار هم بدون هم‌پوشانی یا فواصل قرار می‌گیرند.
* 100%: حداکثر هم‌پوشانی (نوارها کاملاً یک‌دیگر را می‌پوشانند). این ویژگی خواندنی/نوشتنی **int8_t**.

مثال زیر نشان می‌دهد چگونه هم‌پوشانی یک گروه سری نمودار را تنظیم کرده و نمودار حاصل را روی یک فرم رندر کنید: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // همپوشانی را به 55٪ تنظیم کنید

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## موارد مرتبط

* کلاس [IChartSeriesGroup](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)