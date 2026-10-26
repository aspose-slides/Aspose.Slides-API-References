---
title: CalculateFormulas()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: वर्कबुक में सभी सूत्रों की गणना करता है और संबंधित सेल मानों को अपडेट करता है।
type: docs
weight: 14
url: /hi/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() विधि

वर्कबुक में सभी सूत्रों की गणना करता है और संबंधित सेल मानों को अपडेट करता है।

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## टिप्पणी

उदाहरण दिखाता है कि कैसे सूत्र को सेल को सौंपें और मान की गणना करें। "B4" सेल का मान 5 पर सेट किया जा रहा है। 
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

## देखें

* क्लास [IChartDataWorkbook](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)