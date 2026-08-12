---
title: get_UseSecondaryCategories()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "यदि false पर सेट किया जाता है तो ChartData::get_SecondaryCategories null लौटाता है और ChartData::get_Categories में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि true पर सेट किया जाता है तो ChartData::get_SecondaryCategories में डेटा द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है और ChartData::get_Categories में डेटा प्राथमिक श्रृंखलाओं के लिए उपयोग किया जाता है। Read bool."
type: docs
weight: 53
url: /hi/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() विधि

यदि false पर सेट किया जाता है तो [ChartData::get_SecondaryCategories](../get_secondarycategories/) null लौटाता है और [ChartData::get_Categories](../get_categories/) में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए प्रयोग किया जाता है। यदि true पर सेट किया जाता है तो [ChartData::get_SecondaryCategories](../get_secondarycategories/) में डेटा द्वितीयक श्रृंखलाओं के लिए और [ChartData::get_Categories](../get_categories/) में डेटा प्राथमिक श्रृंखलाओं के लिए प्रयोग किया जाता है। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## टिप्पणी

उदाहरण। श्रृंखलाओं से संबंधित श्रेणियां कौन सी हैं - [ChartData::get_Categories](../get_categories/) या [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // संबंधित श्रेणियां series->get_Chart()->get_ChartData()->get_SecondaryCategories() हैं
}
else
{
    // संबंधित श्रेणियां series->get_Chart()->get_ChartData()->get_Categories() हैं
}
```

## देखें भी

* क्लास [ChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)