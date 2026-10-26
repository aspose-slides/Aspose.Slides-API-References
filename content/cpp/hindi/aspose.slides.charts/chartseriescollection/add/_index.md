---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) विधि

नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | श्रृंखला का प्रकार |

### रिटर्न मान

नया चार्ट श्रृंखला।

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) विधि

[ChartDataCell](../../chartdatacell/) से नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) जो श्रृंखला नाम रखता है। |
| type | [ChartType](../../charttype/) | श्रृंखला प्रकार सेट करने का प्रकार |

### रिटर्न मान

संग्रह में पहले से मौजूद श्रृंखला या जोड़ी गई चार्ट श्रृंखला।

## टिप्पणी

यदि समान सेल से बनाई गई चार्ट श्रृंखला पहले से संग्रह में है तो विधि कुछ नहीं जोड़ती और उसका इंडेक्स लौटाती है।

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) विधि

[ChartCellCollection](../../chartcellcollection/) से नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | सेल जो श्रृंखला नाम रखते हैं। |
| type | [ChartType](../../charttype/) | श्रृंखला प्रकार सेट करने का प्रकार |

### रिटर्न मान

संग्रह में पहले से मौजूद श्रृंखला या जोड़ी गई चार्ट श्रृंखला।

## टिप्पणी

यदि समान सेल से बनाई गई चार्ट श्रृंखला पहले से संग्रह में है तो विधि कुछ नहीं जोड़ती और उसका इंडेक्स लौटाती है।

## ChartSeriesCollection::Add(System::String, ChartType) विधि

मान से नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | श्रृंखला नाम। |
| type | [ChartType](../../charttype/) | श्रृंखला प्रकार सेट करने का प्रकार |

### रिटर्न मान

जोड़ी गई चार्ट श्रृंखला।

## देखें

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartSeries](../../ichartseries/)
* क्लास [ChartSeriesCollection](../)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartCellCollection](../../ichartcellcollection/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)