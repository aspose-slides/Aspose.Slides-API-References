---
title: get_SecondaryCategories()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "यदि ChartData::get_UseSecondaryCategories सत्य है तो द्वितीयक श्रेणियों को प्राप्त करता है। केवल-पढ़ने योग्य IChartCategoryCollection."
type: docs
weight: 79
url: /hi/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() विधि

यदि [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) सत्य है तो द्वितीयक श्रेणियों को प्राप्त करता है। केवल पढ़ने योग्य [IChartCategoryCollection](../../ichartcategorycollection/)।

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## टिप्पणी

यदि [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को false सेट किया जाता है तो [ChartData::get_SecondaryCategories](./) null लौटाता है और [ChartData::get_Categories](../get_categories/) में डेटा प्राथमिक और द्वितीयक दोनों श्रृंखला के लिए उपयोग किया जाता है। यदि [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) को true सेट किया जाता है तो [ChartData::get_SecondaryCategories](./) में डेटा द्वितीयक श्रृंखला के लिए और [ChartData::get_Categories](../get_categories/) में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।

उदाहरण। कौन सी श्रेणियाँ श्रृंखला से संबंधित हैं - [ChartData::get_Categories](../get_categories/) या [ChartData::get_SecondaryCategories](./)?
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

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartCategoryCollection](../../ichartcategorycollection/)
* क्लास [ChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)