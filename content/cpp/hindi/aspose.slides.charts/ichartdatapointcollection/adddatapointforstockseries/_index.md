---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API संदर्भ
description: नई डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType स्टॉक उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeStock(ChartType) method)।
type: docs
weight: 144
url: /hi/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) मेथड

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType स्टॉक उपप्रकारों में से एक है ([ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) मेथड को भी देखें)।

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | डेटा पॉइंट मान। |

### रिटर्न वैल्यू

नई डेटा पॉइंट।

## IChartDataPointCollection::AddDataPointForStockSeries(double) मेथड

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType स्टॉक उपप्रकारों में से एक है ([ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) मेथड को भी देखें)।

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **double** | डेटा पॉइंट मान। |

### रिटर्न वैल्यू

नई डेटा पॉइंट।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartDataPointCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)