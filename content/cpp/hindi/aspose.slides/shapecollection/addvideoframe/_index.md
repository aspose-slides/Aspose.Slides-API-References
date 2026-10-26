---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया वीडियो फ्रेम बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 209
url: /hi/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) विधि

एक नया वीडियो फ्रेम बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | [System::String](../../../system/string/) | एम्बेड करने के लिए वीडियो फ़ाइल का पथ या नाम। |

### वापसी मान

नया बनाया गया [IVideoFrame](../../ivideoframe/)।

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) विधि

एक नया वीडियो फ्रेम बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | वीडियो फ्रेम में एम्बेड करने के लिए [IVideo](../../ivideo/)। |

### वापसी मान

नया बनाया गया [IVideoFrame](../../ivideoframe/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IVideoFrame](../../ivideoframe/)
* क्लास [String](../../../system/string/)
* क्लास [ShapeCollection](../)
* क्लास [IVideo](../../ivideo/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)