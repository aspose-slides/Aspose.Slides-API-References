---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्कशीट्स का संग्रह प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() विधि


वर्कशीट्स का संग्रह प्राप्त करता है।

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* क्लास [IChartDataWorkbook](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)