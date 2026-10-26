---
title: get_FadeInDuration()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मीडिया के प्रारम्भिक फ़ेड-इन की समय अवधि मिलीसेकंड में निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 326
url: /hi/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() विधि


मीडिया के प्रारम्भिक फ़ेड-इन की समय अवधि मिलीसेकंड में निर्दिष्ट करता है। पढ़ें **float**।

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// प्रारम्भिक फ़ेड की अवधि 200ms के लिए सेट करें
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)