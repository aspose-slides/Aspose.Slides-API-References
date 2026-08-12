---
title: set_TrimFromStart()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाली समय अवधि को मिलिसैकण्ड में निर्दिष्ट करता है। लिखें **float**.
type: docs
weight: 417
url: /hi/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) मेथड


प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// शुरूआती ट्रिमिंग समय 1.5 सेकंड सेट करें
audioFrame->set_TrimFromStart(1500.0f);
```

## संबंधित देखें

* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)