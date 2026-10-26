---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नई ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है।
type: docs
weight: 261
url: /hi/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) मेथड

एक नई ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है।

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | ऑडियो फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WAV ऑडियो डेटा रखने वाला इनपुट स्ट्रीम जिसे एम्बेड किया जाएगा। |

### रिटर्न वैल्यू

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) मेथड

एक नई ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है, Presentation.Audios सूची से एक मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | ऑडियो फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Presentation.Audios संग्रह से एक [IAudio](../../iaudio/) इंस्टेंस जिसे एम्बेड किया जाएगा। |

### रिटर्न वैल्यू

नया बनाया गया [IAudioFrame](../../iaudioframe/)।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)