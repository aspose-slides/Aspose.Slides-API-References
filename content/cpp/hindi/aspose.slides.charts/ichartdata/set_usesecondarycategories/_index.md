---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यदि इसे false पर सेट किया जाता है तो IChartData::get_SecondaryCategories null लौटाता है और IChartData::get_Categories में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि इसे true पर सेट किया जाता है तो IChartData::get_SecondaryCategories में डेटा द्वितीयक श्रृंखला के लिए और IChartData::get_Categories में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है। bool लिखें।"
type: docs
weight: 66
url: /hi/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) विधि


यदि इसे false पर सेट किया जाता है तो [IChartData::get_SecondaryCategories](../get_secondarycategories/) null लौटाता है और [IChartData::get_Categories](../get_categories/) में डेटा प्राथमिक और द्वितीयक श्रृंखलाओं दोनों के लिए उपयोग किया जाता है। यदि इसे true पर सेट किया जाता है तो [IChartData::get_SecondaryCategories](../get_secondarycategories/) में डेटा द्वितीयक श्रृंखला के लिए और [IChartData::get_Categories](../get_categories/) में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है। **bool** लिखें।

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## टिप्पणियाँ


उदाहरण। श्रृंखला से संबंधित श्रेणियाँ कौन सी हैं - ChartData.Categories या ChartData.SecondaryCategories? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // संबंधित श्रेणियाँ हैं series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // संबंधित श्रेणियाँ हैं series->get_Chart()->get_ChartData()->get_Categories()
}
```

## देखें

* क्लास [IChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)