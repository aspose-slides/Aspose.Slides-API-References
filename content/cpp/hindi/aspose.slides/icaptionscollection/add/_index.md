---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संकलन के अंत में WebVTT बंद कैप्शन जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) मेथड

संकलन के अंत में WebVTT बंद कैप्शन जोड़ता है।

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### आर्ग्यूमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | बंद कैप्शन का लेबल। |
| filePath | [System::String](../../../system/string/) | WebVTT फ़ाइल का पथ। |

### रिटर्न वैल्यू

जोड़ा गया [ICaptions](../../icaptions/) इंस्टेंस।

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) मेथड

स्ट्रीम से WebVTT बंद कैप्शन को संकलन के अंत में जोड़ता है।

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### आर्ग्यूमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | बंद कैप्शन का लेबल। |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT प्रारूप में डेटा वाली इनपुट स्ट्रीम। |

### रिटर्न वैल्यू

जोड़ा गया [ICaptions](../../icaptions/) इंस्टेंस।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ICaptions](../../icaptions/)
* क्लास [String](../../../system/string/)
* क्लास [ICaptionsCollection](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)