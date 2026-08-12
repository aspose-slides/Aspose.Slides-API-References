---
title: AddVideoFrame()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया वीडियो फ्रेम बनाता है और उसे shape collection के अंत में जोड़ता है।
type: docs
weight: 170
url: /hi/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) method

एक नया वीडियो फ्रेम बनाता है और उसे shape collection के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | [System::String](../../../system/string/) | एम्बेड करने के लिए वीडियो फ़ाइल का पाथ या नाम। |

### Return Value

नया बनाया गया [IVideoFrame](../../ivideoframe/)।

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) method

एक नया वीडियो फ्रेम बनाता है और उसे shape collection के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | वीडियो फ्रेम में एम्बेड करने के लिए [IVideo](../../ivideo/)। |

### Return Value

नया बनाया गया [IVideoFrame](../../ivideoframe/)।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IVideoFrame](../../ivideoframe/)
* क्लास [String](../../../system/string/)
* क्लास [IShapeCollection](../)
* क्लास [IVideo](../../ivideo/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)