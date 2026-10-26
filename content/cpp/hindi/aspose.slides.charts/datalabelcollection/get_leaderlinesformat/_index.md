---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा लेबल लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य IChartLinesFormat.
type: docs
weight: 66
url: /hi/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() विधि

डेटा लेबल लीडर लाइन्स फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartLinesFormat](../../ichartlinesformat/)
* क्लास [DataLabelCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)