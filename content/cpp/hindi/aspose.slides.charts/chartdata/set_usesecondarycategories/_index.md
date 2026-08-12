---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यदि false सेट किया गया है तो ChartData::get_SecondaryCategories null लौटाता है और ChartData::get_Categories में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखला के लिए उपयोग होता है। यदि true सेट किया गया है तो ChartData::get_SecondaryCategories में डेटा द्वितीयक श्रृंखला के लिए उपयोग होता है और ChartData::get_Categories में डेटा प्राथमिक श्रृंखला के लिए उपयोग होता है। Write bool."
type: docs
weight: 66
url: /hi/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) विधि


यदि false सेट किया गया है तो [ChartData::get_SecondaryCategories](../get_secondarycategories/) null लौटाता है और [ChartData::get_Categories](../get_categories/) में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखला के लिए उपयोग किया जाता है। यदि true सेट किया गया है तो [ChartData::get_SecondaryCategories](../get_secondarycategories/) में डेटा द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और [ChartData::get_Categories](../get_categories/) में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है। लिखें **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## टिप्पणियां


उदाहरण। कौन सी श्रेणियां श्रृंखला से संबंधित हैं - [ChartData::get_Categories](../get_categories/) या [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* क्लास [ChartData](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)