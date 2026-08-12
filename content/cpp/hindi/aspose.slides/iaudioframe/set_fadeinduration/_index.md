---
title: set_FadeInDuration()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मीडिया के प्रारंभिक फ़ेड-इन की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। float लिखें।
type: docs
weight: 339
url: /hi/aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) विधि


मीडिया के प्रारंभिक फ़ेड-इन की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। **float** लिखें।

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* वर्ग [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)