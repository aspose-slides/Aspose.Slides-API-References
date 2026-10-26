---
title: get_FadeOutDuration()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: मीडिया के अंत में फेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 352
url: /hi/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() विधि


मीडिया के अंत में फेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// समाप्ति फ़ेड की अवधि को 500ms के लिए सेट करें
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [AudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)