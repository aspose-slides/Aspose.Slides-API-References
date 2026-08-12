---
title: get_VolumeValue()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑडियो वॉल्यूम को प्रतिशत में लौटाता है। पढ़ें float.
type: docs
weight: 378
url: /hi/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() मेथड


ऑडियो वॉल्यूम को प्रतिशत में लौटाता है। पढ़ें **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ़्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// प्रारम्भिक फेड की अवधि 200ms के लिए सेट करें
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [AudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)