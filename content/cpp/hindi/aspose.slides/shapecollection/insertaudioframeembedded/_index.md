---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर shape संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation::get_Audios संग्रह में जोड़ा जाता है।"
type: docs
weight: 300
url: /hi/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) विधि

एक नया ऑडियो फ्रेम बनाता है जिसमें सम्मिलित WAV फ़ाइल होती है और इसे निर्दिष्ट अनुक्रमांक पर shape संग्रह में सम्मिलित करता है। सम्मिलित ऑडियो को [Presentation::get_Audios](../../presentation/get_audios/) संग्रह में जोड़ा जाता है।

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | ऑडियो फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एंबेड करने के लिए WAV ऑडियो डेटा वाली इनपुट स्ट्रीम। |

### वापसी मान

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) विधि

एक नया ऑडियो फ्रेम बनाता है और निर्दिष्ट अनुक्रमांक पर shape संग्रह में इसे सम्मिलित करता है, [Presentation::get_Audios](../../presentation/get_audios/) सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | ऑडियो फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | एंबेड करने के लिए [Presentation::get_Audios](../../presentation/get_audios/) संग्रह से एक [IAudio](../../iaudio/) इंस्टेंस। |

### वापसी मान

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudioFrame](../../iaudioframe/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [ShapeCollection](../)
* क्लास [IAudio](../../iaudio/)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)