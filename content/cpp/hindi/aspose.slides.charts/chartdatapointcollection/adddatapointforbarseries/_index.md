---
title: AddDataPointForBarSeries()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Column या Bar उप-प्रकारों में से एक है (देखें ChartTypeCharacterizer::IsChartTypeColumn(ChartType) और ChartTypeCharacterizer::IsChartTypeBar(ChartType) मेथड)।"
type: docs
weight: 261
url: /hi/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) विधि

नए डेटा पॉइंट को बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType [Column](../../../aspose.slides/column/) या Bar उप-प्रकारों में से एक है (देखें [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) और [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) विधि)।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा पॉइंट मान |

### रिटर्न वैल्यू

नया डेटा पॉइंट।

## ChartDataPointCollection::AddDataPointForBarSeries(double) विधि

नए डेटा पॉइंट को बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType [Column](../../../aspose.slides/column/) या Bar उप-प्रकारों में से एक है (देखें [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) और [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) विधि)।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | डेटा पॉइंट मान |

### रिटर्न वैल्यू

नया डेटा पॉइंट।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [ChartDataPointCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)