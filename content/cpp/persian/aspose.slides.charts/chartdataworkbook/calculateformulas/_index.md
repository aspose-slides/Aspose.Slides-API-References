---
title: CalculateFormulas()
second_title: مرجع API Aspose.Slides برای C++
description: تمام فرمول‌ها را در کتاب کار محاسبه می‌کند و مقادیر سلول‌های مربوطه را به روز می‌سازد.
type: docs
weight: 53
url: /fa/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() متد


تمام فرمول‌ها را در کتاب کار محاسبه می‌کند و مقادیر سلول‌های مربوطه را به‌روز می‌سازد.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## توضیحات



مثال نشان می‌دهد چگونه یک فرمول را به سلول اختصاص داده و مقدار آن را محاسبه کنیم. مقدار سلول \"B4\" به 5 تنظیم می‌شود.
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## موارد مرتبط

* کلاس [ChartDataWorkbook](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)