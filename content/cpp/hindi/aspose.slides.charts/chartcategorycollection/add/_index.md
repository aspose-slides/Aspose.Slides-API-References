---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि संग्रह में वर्ग मौजूद है, तो उसे वापस करें। अन्यथा IChartDataCell से नया चार्ट वर्ग बनाते हैं और उसे संग्रह में जोड़ते हैं।
type: docs
weight: 92
url: /hi/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) विधि


यदि संग्रह में वर्ग मौजूद है, तो उसे वापस करें। अन्यथा [IChartDataCell](../../ichartdatacell/) से नया चार्ट वर्ग बनाते हैं और उसे संग्रह में जोड़ते हैं।

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) का उपयोग करके चार्ट वर्ग बनाया जाता है। |

### रिटर्न मान

जोड़ा गया या मौजूदा वर्ग।



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) विधि


मान से नया [ChartCategory](../../chartcategory/) बनाते हैं और उसे संग्रह में जोड़ते हैं।

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | मान। |

### रिटर्न मान

जोड़ा गया [IChartCategory](../../ichartcategory/)।
## टिप्पणी



यह विधि AUTO_DATA नाम की वर्कशीट जोड़ती है और सभी मानों को वहाँ जोड़ती है। यदि आप [ChartDataWorkbook](../../chartdataworkbook/) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस वर्कशीट का उपयोग न करें। इस विधि द्वारा जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।



## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)