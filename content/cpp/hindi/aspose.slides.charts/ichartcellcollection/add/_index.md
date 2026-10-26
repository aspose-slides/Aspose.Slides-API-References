---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कॉलेक्शन में नया सेल जोड़ें।
type: docs
weight: 53
url: /hi/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method


कॉलेक्शन में नया सेल जोड़ें।

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | जोड़ने के लिए नया सेल। |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) method


निर्दिष्ट मान से [IChartDataCell](../../ichartdatacell/) बनाता है और इसे कॉलेक्शन में जोड़ता है।

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | मान। |
## टिप्पणियाँ



यह मेथड नाम AUTO_DATA वाली वर्कशीट जोड़ता है और सभी मान वहाँ जोड़ता है। यदि आप [IChartDataWorkbook](../../ichartdataworkbook/) का उपयोग करके [Cell](../../../aspose.slides/cell/) मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस वर्कशीट का उपयोग न करें। इस मेथड का उपयोग करके जोड़े जाने वाले मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए



## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [IChartCellCollection](../)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)