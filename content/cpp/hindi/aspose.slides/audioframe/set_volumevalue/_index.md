---
title: set_VolumeValue()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑडियो वॉल्यूम को प्रतिशत में सेट करता है। लिखें float.
type: docs
weight: 391
url: /hi/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) विधि

ऑडियो वॉल्यूम को प्रतिशत में सेट करता है। लिखें **float**।

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// प्रारंभिक फेड की अवधि 200ms के लिए सेट करें
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [AudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)