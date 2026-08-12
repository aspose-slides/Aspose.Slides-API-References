---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संकलन में नया सेल जोड़ें।
type: docs
weight: 53
url: /hi/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) मेथड

संकलन में नया सेल जोड़ें।

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | जोड़ने के लिए नया सेल। |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) मेथड

निर्दिष्ट मान से [ChartDataCell](../../chartdatacell/) बनाता है और इसे संकलन में जोड़ता है।

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | मान। |

## टिप्पणियाँ

यह मेथड नाम AUTO_DATA वाली वर्कशीट जोड़ता है और सभी मानों को वहाँ जोड़ता है। यदि आप [ChartDataWorkbook](../../chartdataworkbook/) का उपयोग करके [Cell](../../../aspose.slides/cell/) मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस वर्कशीट का उपयोग न करें। इस मेथड का उपयोग करके जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataCell](../../ichartdatacell/)
* क्लास [ChartCellCollection](../)
* क्लास [Object](../../../system/object/)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)