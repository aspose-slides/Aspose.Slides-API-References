---
title: get_TrimFromEnd()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 430
url: /hi/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() विधि

प्लेबैक के दौरान मीडिया के अंत से हटाने के लिए निर्दिष्ट समय अवधि, मिलीसेकंड में। पढ़ें **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ़्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// अंत ट्रिमिंग समय 2 सेकंड सेट करें
audioFrame->set_TrimFromEnd(2000.0f);
```

## देखें

* क्लास [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)