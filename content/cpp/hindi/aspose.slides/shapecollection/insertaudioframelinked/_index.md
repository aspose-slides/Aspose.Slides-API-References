---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नई ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ी होती है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।
type: docs
weight: 274
url: /hi/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) विधि

एक नया ऑडियो फ़्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा होता है और इसे निर्दिष्ट सूचकांक पर शेप कलेक्शन में सम्मिलित करता है।

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित सूचकांक जहाँ ऑडियो फ़्रेम सम्मिलित किया जाएगा। |
| x | **float** | नए ऑडियो फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट्स में। |
| fname | [System::String](../../../system/string/) | बाहरी ऑडियो फ़ाइल का पथ या नाम जिससे लिंक किया जाना है। |

### वापसी मान

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudioFrame](../../iaudioframe/)
* क्लास [String](../../../system/string/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)