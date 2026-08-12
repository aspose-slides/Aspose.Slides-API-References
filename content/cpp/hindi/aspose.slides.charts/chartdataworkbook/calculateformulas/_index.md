---
title: CalculateFormulas()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्कबुक में सभी फ़ॉर्मूलों की गणना करता है और संबंधित सेल मानों को अपडेट करता है।
type: docs
weight: 53
url: /hi/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() विधि

वर्कबुक में सभी फ़ॉर्मूलों की गणना करता है और संबंधित सेल मानों को अपडेट करता है।

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## टिप्पणियाँ



उदाहरण दर्शाता है कि कैसे फ़ॉर्मूला को सेल को सौंपा जाए और मान की गणना की जाए। \"B4\" सेल का मान 5 पर सेट किया जा रहा है। 
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

## संबंधित देखें

* क्लास [ChartDataWorkbook](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)