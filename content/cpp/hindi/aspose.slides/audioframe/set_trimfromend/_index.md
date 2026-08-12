---
title: set_TrimFromEnd()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। float लिखें।
type: docs
weight: 443
url: /hi/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) मेथड


प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। **float** लिखें।

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## टिप्पणी


उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// समाप्ति ट्रिमिंग समय 2 सेकंड सेट करें
audioFrame->set_TrimFromEnd(2000.0f);
```

## देखें

* क्लास [AudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)