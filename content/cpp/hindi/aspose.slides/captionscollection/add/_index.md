---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) विधि

संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | बंद कैप्शन का लेबल। |
| filePath | [System::String](../../../system/string/) | WebVTT फ़ाइल का पथ। |

### वापसी मान

जोड़ा गया [ICaptions](../../icaptions/) इंस्टेंस।

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) विधि

स्ट्रीम से संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | बंद कैप्शन का लेबल। |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT फ़ॉर्मेट में डेटा रखने वाला इनपुट स्ट्रीम। |

### वापसी मान

जोड़ा गया [ICaptions](../../icaptions/) इंस्टेंस।

## संबंधित

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ICaptions](../../icaptions/)
* क्लास [String](../../../system/string/)
* क्लास [CaptionsCollection](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)