---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides for C++ API संदर्भ
description: "नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType पाई उपप्रकारों में से एक है (देखें ChartTypeCharacterizer::IsChartTypePie(ChartType) विधि)।"
type: docs
weight: 287
url: /hi/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) विधि

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। ऐसी श्रृंखला के लिए लागू है जिनका chartType पाई उपप्रकारों में से एक है (देखें [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) विधि)।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा बिंदु मान |

### वापसी मान

नया डेटा बिंदु।

## ChartDataPointCollection::AddDataPointForPieSeries(double) विधि

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। ऐसी श्रृंखला के लिए लागू है जिनका chartType पाई उपप्रकारों में से एक है (देखें [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) विधि)।

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | डेटा बिंदु मान |

### वापसी मान

नया डेटा बिंदु।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)