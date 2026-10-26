---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे शैप कलेक्शन के अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation.Audios कलेक्शन में जोड़ा जाता है।
type: docs
weight: 248
url: /hi/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे शैप कलेक्शन के अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation.Audios कलेक्शन में जोड़ा जाता है।

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए ऑडियो फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊंचाई, पॉइंट्स में। |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एम्बेड करने के लिए WAV ऑडियो डेटा वाला इनपुट स्ट्रीम। |

### रिटर्न वैल्यू

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

एक नया ऑडियो फ्रेम बनाता है और इसे शैप कलेक्शन के अंत में जोड़ता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | नए ऑडियो फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊंचाई, पॉइंट्स में। |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Presentation.Audios कलेक्शन से एक [IAudio](../../iaudio/) इंस्टेंस। |

### रिटर्न वैल्यू

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)