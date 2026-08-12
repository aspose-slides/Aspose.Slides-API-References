---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides for C++ API संदर्भ
description: नया डेटा पॉइंट बनाता है और उसे संग्रह के अंत में जोड़ता है। वह श्रृंखला के लिए लागू है जिसका चार्ट प्रकार मानचित्र है।
type: docs
weight: 352
url: /hi/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) विधि

नया डेटा पॉइंट बनाता है और उसे संग्रह के अंत में जोड़ता है। यह उस श्रृंखला के लिए लागू है जिसका चार्ट प्रकार मैप है।

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा पॉइंट ColorValue |

### रिटर्न मान

नया डेटा पॉइंट।

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartDataPointCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)