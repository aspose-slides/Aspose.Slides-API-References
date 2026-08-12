---
title: set_FadeOutDuration()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: मीडिया के अंत फ़ेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। float लिखें।
type: docs
weight: 365
url: /hi/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) method


मीडिया के अंत फ़ेड-आउट की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## टिप्पणियाँ


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

## संबंधित देखें

* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)