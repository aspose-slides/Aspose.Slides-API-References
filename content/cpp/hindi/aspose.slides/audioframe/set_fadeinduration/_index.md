---
title: set_FadeInDuration()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: मीडिया के प्रारंभिक फ़ेड-इन की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें float.
type: docs
weight: 339
url: /hi/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) विधि


मीडिया के प्रारंभिक फ़ेड-इन की समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// प्रारंभिक फेड की अवधि को 200ms के लिए सेट करें
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## और देखें

* वर्ग [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)