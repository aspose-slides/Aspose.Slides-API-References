---
title: AddTable()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया टेबल बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।
type: docs
weight: 430
url: /hi/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) विधि

एक नया टेबल बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | डबल्स की एक ऐरे जो टेबल के कॉलम की चौड़ाइयों को दर्शाता है, पॉइंट्स में। |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | डबल्स की एक ऐरे जो टेबल के पंक्तियों की ऊँचाइयों को दर्शाता है, पॉइंट्स में। |

### रिटर्न मान

नया बनाया गया [ITable](../../itable/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)