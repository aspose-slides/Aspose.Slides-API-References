---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नई ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से लिंक्ड होती है और निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करती है।
type: docs
weight: 235
url: /hi/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) विधि

एक नई ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से लिंक्ड होती है और निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करती है।

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | वह शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम को सम्मिलित किया जाना है। |
| x | **float** | नई ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नई ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नई ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नई ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | [System::String](../../../system/string/) | लिंक करने के लिए बाहरी ऑडियो फ़ाइल का पथ या नाम। |

### रिटर्न मान

नया निर्मित [IAudioFrame](../../iaudioframe/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudioFrame](../../iaudioframe/)
* क्लास [String](../../../system/string/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)