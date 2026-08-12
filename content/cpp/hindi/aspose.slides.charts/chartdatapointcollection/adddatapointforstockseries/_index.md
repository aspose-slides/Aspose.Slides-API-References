---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API संदर्भ
description: "नई डेटा पॉइंट बनाता है और इसे कलेक्शन के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Stock उपप्रकारों में से एक है (देखें ChartTypeCharacterizer::IsChartTypeStock(ChartType) मेथड)।"
type: docs
weight: 209
url: /hi/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) मेथड

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Stock उपप्रकारों में से एक है (देखें [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) मेथड)।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा पॉइंट मान। |

### Return Value

नया डेटा पॉइंट।

## ChartDataPointCollection::AddDataPointForStockSeries(double) मेथड

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Stock उपप्रकारों में से एक है (देखें [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) मेथड)।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **double** | डेटा पॉइंट मान। |

### Return Value

नया डेटा पॉइंट।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)