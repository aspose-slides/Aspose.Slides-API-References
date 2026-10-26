---
title: get_TrimFromEnd()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्लेबैक के दौरान मीडिया के अंत से हटाई जाने वाली समय अवधि को मिलीसेकंड में निर्धारित करता है। पढ़ें float.
type: docs
weight: 430
url: /hi/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() विधि

निर्धारित करता है कि प्लेबैक के दौरान मीडिया के अंत से हटाने के लिए समय अवधि मिलिसेकंड में क्या होनी चाहिए। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// अंतिम ट्रिमिंग समय 2 सेकंड सेट करें
audioFrame->set_TrimFromEnd(2000.0f);
```

## संबंधित देखें

* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)