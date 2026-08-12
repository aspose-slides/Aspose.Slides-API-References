---
title: set_VolumeValue()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑडियो वॉल्यूम को प्रतिशत में सेट करता है। float लिखें।
type: docs
weight: 391
url: /hi/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) विधि

ऑडियो की मात्रा प्रतिशत में सेट करता है। **float** लिखें।

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ़्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// प्रारंभिक फ़ेड की अवधि को 200ms के लिए सेट करें
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)