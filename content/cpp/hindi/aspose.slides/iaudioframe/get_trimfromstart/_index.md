---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 404
url: /hi/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() method

प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के लिए समय अवधि को निर्दिष्ट करता है, मिलीसेकंड में। पढ़ें **float**।

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ़्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// प्रारंभिक ट्रिमिंग समय 1.5 सेकंड सेट करें
audioFrame->set_TrimFromStart(1500.0f);
```

## देखें भी

* क्लास [IAudioFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)