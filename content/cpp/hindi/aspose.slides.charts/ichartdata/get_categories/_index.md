---
title: get_Categories()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "प्राथमिक श्रेणियों को प्राप्त करता है (या यदि IChartData::set_UseSecondaryCategories को false सेट किया गया है तो प्राथमिक और द्वितीयक दोनों श्रेणियाँ)। केवल-पढ़ने योग्य IChartCategoryCollection."
type: docs
weight: 40
url: /hi/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() मेथड

प्राथमिक श्रेणियों को प्राप्त करता है (या यदि [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को false सेट किया गया है तो प्राथमिक और द्वितीयक दोनों श्रेणियों को)। केवल-पढ़ने योग्य [IChartCategoryCollection](../../ichartcategorycollection/)।

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## टिप्पणी

यदि [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को false सेट किया गया है तो [IChartData::get_SecondaryCategories](../get_secondarycategories/) null लौटाता है और [IChartData::get_Categories](./) में डेटा प्राथमिक और द्वितीयक श्रृंखलाओं दोनों के लिए उपयोग किया जाता है। यदि [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को true सेट किया गया है तो [IChartData::get_SecondaryCategories](../get_secondarycategories/) में डेटा द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और [IChartData::get_Categories](./) में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।

उदाहरण। कौन सी श्रेणियां श्रृंखलाओं से संबंधित हैं - ChartData.Categories या ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartCategoryCollection](../../ichartcategorycollection/)
* क्लास [IChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)