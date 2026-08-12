---
title: FromStream()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट स्ट्रीम से एक Image ऑब्जेक्ट बनाता है।
type: docs
weight: 339
url: /hi/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) विधि

[Image](../) ऑब्जेक्ट को निर्दिष्ट स्ट्रीम से बनाता है।

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | इमेज डेटा युक्त एक स्ट्रीम |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### रिटर्न मान

बनाए गए [Image](../) ऑब्जेक्ट का शेयर्ड पॉइंटर।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Image](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)