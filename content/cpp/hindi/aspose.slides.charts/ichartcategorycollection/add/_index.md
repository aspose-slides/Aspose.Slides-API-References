---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि संग्रह में श्रेणी मौजूद है, तो उसे लौटाएँ। अन्यथा IChartDataCell से नया चार्ट श्रेणी बनाता है और इसे संग्रह में जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) विधि

यदि संग्रह में श्रेणी मौजूद है, तो उसे लौटाएँ। अन्यथा [IChartDataCell](../../ichartdatacell/) से नया चार्ट श्रेणी बनाता है और उसे संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) का उपयोग चार्ट श्रेणी बनाने के लिए किया जाता है। |

### Return Value

जोड़े गए या मौजूदा श्रेणी।

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) विधि

[IChartCategory](../../ichartcategory/) को मान से बनाता है और उसे संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | मान। |

### Return Value

जोड़ा गया [IChartCategory](../../ichartcategory/)।

## टिप्पणी

यह विधि AUTO_DATA नाम के साथ एक कार्यपत्र जोड़ती है और सभी मान वहाँ जोड़ती है। यदि आप [IChartDataWorkbook](../../ichartdataworkbook/) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्र का उपयोग न करें। इस विधि का उपयोग करके जोड़े जा सकने वाले मानों की अधिकतम संख्या 16711680 नहीं होनी चाहिए।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartCategory](../../ichartcategory/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartCategoryCollection](../)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)