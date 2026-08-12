---
title: set_FadeOutDuration()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मीडिया के समाप्ति फेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें float.
type: docs
weight: 365
url: /hi/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) विधि


मीडिया के समाप्ति फेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**।

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// समाप्ति फेड की अवधि को 500ms के लिए सेट करें
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)