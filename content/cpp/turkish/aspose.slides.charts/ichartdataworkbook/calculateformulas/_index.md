---
title: CalculateFormulas()
second_title: Aspose.Slides için C++ API Referansı
description: Çalışma kitabındaki tüm formülleri hesaplar ve ilgili hücre değerlerini günceller.
type: docs
weight: 14
url: /tr/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() metodu

Çalışma kitabındaki tüm formülleri hesaplar ve ilgili hücre değerlerini günceller.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Açıklamalar

Örnek, bir hücreye formül atamayı ve bir değeri hesaplamayı gösterir. "B4" hücresinin değeri 5 olarak ayarlanır.

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

## İlgili

* Sınıf [IChartDataWorkbook](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)