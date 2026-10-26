---
title: get_Categories()
second_title: Aspose.Slides for C++ API संदर्भ
description: "प्राथमिक श्रेणियों को प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियों को यदि ChartData::set_UseSecondaryCategories को false सेट किया गया हो)। केवल पढ़ने योग्य IChartCategoryCollection."
type: docs
weight: 40
url: /hi/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() मेथड

प्राथमिक श्रेणियों को प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियों को यदि [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को false सेट किया गया हो)। केवल पढ़ने योग्य [IChartCategoryCollection](../../ichartcategorycollection/)।

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## टिप्पणियाँ

यदि [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को false सेट किया जाता है तो [ChartData::get_SecondaryCategories](../get_secondarycategories/) null लौटाता है और [ChartData::get_Categories](./) में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखलाओं के लिये उपयोग किया जाता है। यदि [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को true सेट किया जाता है तो [ChartData::get_SecondaryCategories](../get_secondarycategories/) में डेटा द्वितीयक श्रृंखलाओं के लिये उपयोग किया जाता है और [ChartData::get_Categories](./) में डेटा प्राथमिक श्रृंखलाओं के लिये उपयोग किया जाता है।

उदाहरण। कौन सी श्रेणियाँ श्रृंखला से सम्बंधित हैं - [ChartData::get_Categories](./) या [ChartData::get_SecondaryCategories](../get_secondarycategories/)?

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartCategoryCollection](../../ichartcategorycollection/)
* क्लास [ChartData](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)