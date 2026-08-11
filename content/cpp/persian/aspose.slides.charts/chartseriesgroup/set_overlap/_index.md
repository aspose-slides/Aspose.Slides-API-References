---
title: set_Overlap()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به صورت درصد (از -100% تا 100%).
type: docs
weight: 170
url: /fa/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) متد

مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## توضیحات

* -100٪: بیشترین فاصله (میله‌ها کاملاً جدا شده‌اند).
* 0٪: میله‌ها کنار یکدیگر بدون هم‌پوشانی یا فاصله قرار می‌گیرند.
* 100٪: بیشترین هم‌پوشانی (میله‌ها کاملاً بر روی یکدیگر قرار می‌گیرند). این ویژگی قابل خواندن/نوشتن است **int8_t**.

مثال زیر نشان می‌دهد که چگونه هم‌پوشانی یک گروه سری‌نمودار را تنظیم کرده و نمودار حاصل را روی فرم رندر کنید: 
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

* کلاس [ChartSeriesGroup](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)