---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक एम्बेडेड WAV फ़ाइल के साथ एक नया ऑडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation::get_Audios कलेक्शन में जोड़ा जाता है।"
type: docs
weight: 287
url: /hi/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) मेथड

एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे शेप कलेक्शन के अंत में जोड़ता है। एम्बेडेड ऑडियो [Presentation::get_Audios](../../presentation/get_audios/) कलेक्शन में जोड़ा जाता है।

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | एक इनपुट स्ट्रीम जिसमें एम्बेड करने के लिए WAV ऑडियो डेटा होता है। |

### रिटर्न वैल्यू

नया निर्मित [IAudioFrame](../../iaudioframe/)।

## टिप्पणियाँ

निम्नलिखित उदाहरण दिखाते हैं कि कैसे [Audio](../../audio/) फ्रेम बनाएं।
```cpp
// एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला प्रस्तुति क्लास बनाता है
auto pres = System::MakeObject<Presentation>();

// पहली स्लाइड प्राप्त करता है
auto slide = pres->get_Slides()->idx_get(0);
// wav ध्वनि फ़ाइल को स्ट्रीम में लोड करता है
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// ऑडियो फ्रेम जोड़ता है
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// ऑडियो के प्ले मोड और वॉल्यूम सेट करता है
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// PowerPoint फ़ाइल को डिस्क पर लिखता है
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) मेथड

एक नया ऑडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, जिसमें [Presentation::get_Audios](../../presentation/get_audios/) सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग किया गया है।

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | एक [IAudio](../../iaudio/) इंस्टेंस जो [Presentation::get_Audios](../../presentation/get_audios/) कलेक्शन से है। |

### रिटर्न वैल्यू

नया निर्मित [IAudioFrame](../../iaudioframe/)।

## और देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudioFrame](../../iaudioframe/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [ShapeCollection](../)
* क्लास [IAudio](../../iaudio/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)