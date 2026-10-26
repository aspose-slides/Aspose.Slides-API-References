---
title: BufferedStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक BufferedStream ऑब्जेक्ट बनाता है जो निर्दिष्ट स्ट्रीम को रैप करता है और 4096 बाइट लंबा बफ़र उपयोग करता है।
type: docs
weight: 1
url: /hi/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) कंस्ट्रक्टर

एक [BufferedStream](../) ऑब्जेक्ट बनाता है जो निर्दिष्ट स्ट्रीम को रैप करता है और 4096 बाइट लंबा बफ़र उपयोग करता है।

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | आधारभूत [Stream](../../stream/) ऑब्जेक्ट |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) कंस्ट्रक्टर

एक [BufferedStream](../) ऑब्जेक्ट बनाता है जो निर्दिष्ट स्ट्रीम को रैप करता है और निर्दिष्ट आकार का बफ़र उपयोग करता है।

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | आधारभूत [Stream](../../stream/) ऑब्जेक्ट |
| bufferSize | int | बफ़र का आकार बाइट में |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../stream/)
* क्लास [BufferedStream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)