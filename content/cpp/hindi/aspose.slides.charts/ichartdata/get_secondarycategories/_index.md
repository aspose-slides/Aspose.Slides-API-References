---
title: get_SecondaryCategories()
second_title: Aspose.Slides C++ API संदर्भ
description: "यदि IChartData::get_UseSecondaryCategories true है तो द्वितीयक श्रेणियों को प्राप्त करता है। केवल-पढ़ने योग्य IChartCategoryCollection."
type: docs
weight: 79
url: /hi/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() मेथड

यदि [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) सत्य है तो द्वितीयक श्रेणियाँ प्राप्त करता है। केवल-पढ़ने योग्य [IChartCategoryCollection](../../ichartcategorycollection/)।

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## टिप्पणी

यदि [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को false सेट किया जाता है तो [IChartData::get_SecondaryCategories](./) null लौटाता है और [IChartData::get_Categories](../get_categories/) में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिए उपयोग किया जाता है। यदि [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को true सेट किया जाता है तो [IChartData::get_SecondaryCategories](./) में डेटा द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और [IChartData::get_Categories](../get_categories/) में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।

उदाहरण। कौन सी श्रेणियाँ श्रृंखला से संबंधित हैं - ChartData.Categories या ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // संबंधित श्रेणियाँ series->get_Chart()->get_ChartData()->get_SecondaryCategories() हैं
}
else
{
    // संबंधित श्रेणियाँ series->get_Chart()->get_ChartData()->get_Categories() हैं
}
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* वर्ग [IChartCategoryCollection](../../ichartcategorycollection/)
* वर्ग [IChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)