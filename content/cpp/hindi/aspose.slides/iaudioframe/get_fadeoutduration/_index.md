---
title: get_FadeOutDuration()
second_title: Aspose.Slides for C++ API संदर्भ
description: मीडिया के अंत में फेड-आउट के लिए समय अवधि को मिलिसेकंड में निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 352
url: /hi/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() मेथड


मीडिया के अंत में फेड-आउट के लिये समय अवधि को मिलिसेकंड में निर्दिष्ट करता है। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// अंतिम फेड की अवधि को 500ms के लिए सेट करें
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [IAudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)