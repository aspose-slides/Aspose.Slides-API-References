---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यदि इसे false पर सेट किया जाता है तो IChartData::get_SecondaryCategories null लौटाता है और IChartData::get_Categories में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि इसे true पर सेट किया जाता है तो IChartData::get_SecondaryCategories में डेटा द्वितीयक श्रृंखलाओं के लिए और IChartData::get_Categories में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग किया जाता है। पढ़ें bool."
type: docs
weight: 53
url: /hi/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() विधि

यदि इसे false पर सेट किया जाता है तो [IChartData::get_SecondaryCategories](../get_secondarycategories/) null लौटाता है और [IChartData::get_Categories](../get_categories/) में डेटा प्राथमिक और द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। यदि इसे true पर सेट किया जाता है तो [IChartData::get_SecondaryCategories](../get_secondarycategories/) में डेटा द्वितीयक सीरीज़ के लिए और [IChartData::get_Categories](../get_categories/) में डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है। पढ़ें **bool**।

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## टिप्पणी

उदाहरण। कौन से श्रेणियां सीरीज़ से संबंधित हैं - ChartData.Categories या ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // संबंधित श्रेणियां हैं series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // संबंधित श्रेणियां हैं series->get_Chart()->get_ChartData()->get_Categories()
}
```

## संबंधित देखें

* क्लास [IChartData](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)