---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API संदर्भ
description: नई डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Line उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeLine(ChartType) विधि).
type: docs
weight: 157
url: /hi/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) विधि

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Line उपप्रकार में से एक है (देखें [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) विधि).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा बिंदु मान। |

### रिटर्न मान

नया डेटा बिंदु।

## IChartDataPointCollection::AddDataPointForLineSeries(double) विधि

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Line उपप्रकार में से एक है (देखें [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) विधि).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **double** | डेटा बिंदु मान। |

### रिटर्न मान

नया डेटा बिंदु।

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartDataPointCollection](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)