---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑडियो वॉल्यूम प्रतिशत में लौटाता है। पढ़ें float.
type: docs
weight: 378
url: /hi/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() विधि

ऑडियो वॉल्यूम प्रतिशत में लौटाता है। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [IAudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)