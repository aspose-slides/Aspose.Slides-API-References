---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नई चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) method

नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | श्रृंखला का प्रकार |

### Return Value

नया चार्ट श्रृंखला।

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) method

[IChartDataCell](../../ichartdatacell/) से नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) जो श्रृंखला नाम रखता है। |
| type | [ChartType](../../charttype/) | श्रृंखला प्रकार निर्धारित करने का प्रकार |

### Return Value

जोड़ा गया चार्ट श्रृंखला या वह श्रृंखला जो पहले से ही संग्रह में मौजूद है।

## Remarks

यदि समान सेल से बना चार्ट श्रृंखला पहले से ही संग्रह में मौजूद है तो मेथड कुछ नहीं जोड़ता और उसका इंडेक्स लौटाता है।

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) method

[IChartCellCollection](../../ichartcellcollection/) से नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cells जो श्रृंखला नाम रखती हैं। |
| type | [ChartType](../../charttype/) | श्रृंखला प्रकार निर्धारित करने का प्रकार |

### Return Value

जोड़ा गया चार्ट श्रृंखला या वह श्रृंखला जो पहले से ही संग्रह में मौजूद है।

## Remarks

यदि समान सेल से बना चार्ट श्रृंखला पहले से ही संग्रह में मौजूद है तो मेथड कुछ नहीं जोड़ता और उसका इंडेक्स लौटाता है।

## IChartSeriesCollection::Add(System::String, ChartType) method

मान से नया चार्ट श्रृंखला बनाता है और इसे संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | श्रृंखला का नाम। |
| type | [ChartType](../../charttype/) | श्रृंखला प्रकार निर्धारित करने का प्रकार |

### Return Value

जोड़ा गया चार्ट श्रृंखला।

## See Also

* एन्यूम [ChartType](../../charttype/)
* टाइपडैफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartSeries](../../ichartseries/)
* क्लास [IChartSeriesCollection](../)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartCellCollection](../../ichartcellcollection/)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)