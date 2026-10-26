---
title: Save()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए चित्र को निर्दिष्ट फ़ाइल में PNG स्वरूप में सहेजता है।
type: docs
weight: 1
url: /hi/system.drawing/image/save/
---
## Image::Save(const String\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए चित्र को निर्दिष्ट फ़ाइल में PNG स्वरूप में सहेजता है।

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | चित्र को सहेजने वाली फ़ाइल का नाम |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए चित्र को निर्दिष्ट फ़ाइल में निर्दिष्ट स्वरूप में सहेजता है।

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | चित्र को सहेजने वाली फ़ाइल का नाम |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | चित्र को सहेजने के लिए स्वरूप |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए चित्र को निर्दिष्ट स्ट्रीम में निर्दिष्ट स्वरूप में सहेजता है।

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | चित्र को सहेजने के लिए स्ट्रीम |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | चित्र को सहेजने के लिए स्वरूप |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए चित्र को निर्दिष्ट एन्कोडर और एन्कोडर पैरामीटरों का उपयोग करके निर्दिष्ट फ़ाइल में सहेजता है।

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | चित्र को सहेजने वाली फ़ाइल का नाम |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | उपयोग करने वाला एन्कोडर |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | उपयोग करने वाले एन्कोडर के पैरामीटर |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए चित्र को निर्दिष्ट एन्कोडर और एन्कोडर पैरामीटरों का उपयोग करके निर्दिष्ट स्ट्रीम में सहेजता है।

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | चित्र को सहेजने के लिए स्ट्रीम |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | उपयोग करने वाला एन्कोडर |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | उपयोग किए जाने वाले एन्कोडर के पैरामीटर |

## संबंधित देखें

* टाइपडिफ [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* टाइपडिफ [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* वर्ग [String](../../../system/string/)
* वर्ग [Image](../)
* वर्ग [Stream](../../../system.io/stream/)
* नामस्थान [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)