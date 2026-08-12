---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्लेबैक के दौरान मीडिया की शुरुआत से हटाई जाने वाली समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। float लिखें।
type: docs
weight: 417
url: /hi/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) मेथड


प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। **float** लिखें।

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ़्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// आरंभिक ट्रिमिंग समय 1.5 सेकंड सेट करें
audioFrame->set_TrimFromStart(1500.0f);
```

## देखें

* क्लास [AudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)