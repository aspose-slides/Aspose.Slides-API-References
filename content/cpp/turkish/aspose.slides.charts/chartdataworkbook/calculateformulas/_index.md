---
title: CalculateFormulas()
second_title: Aspose.Slides for C++ API Referansı
description: Çalışma kitabındaki tüm formülleri hesaplar ve ilgili hücre değerlerini günceller.
type: docs
weight: 53
url: /tr/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() metot


Çalışma kitabındaki tüm formülleri hesaplar ve ilgili hücre değerlerini günceller.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Açıklamalar



Örnek, bir formülü hücreye nasıl atayacağınızı ve bir değeri nasıl hesaplayacağınızı gösterir. \"B4\" hücresinin değeri 5 olarak ayarlanır. 
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

## Ayrıca Bakınız

* Sınıf [ChartDataWorkbook](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)