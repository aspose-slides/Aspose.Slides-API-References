---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नया डेटा बिंदु बनाता है और उसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType पाई उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypePie(ChartType) विधि)।
type: docs
weight: 222
url: /hi/aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries/
---
## IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) विधि


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (देखें [ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) विधि).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा बिंदु मान |

### रिटर्न वैल्यू

नया डेटा बिंदु।

## IChartDataPointCollection::AddDataPointForPieSeries(double) विधि


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (देखें [ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) विधि).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(double value)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **double** | डेटा बिंदु मान |

### रिटर्न वैल्यू

नया डेटा बिंदु।

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartDataPointCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)