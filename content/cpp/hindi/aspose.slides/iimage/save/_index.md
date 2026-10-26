---
title: Save()
second_title: Aspose.Slides for C++ API संदर्भ
description: इमेज को फ़ाइल में सहेजता है।
type: docs
weight: 40
url: /hi/aspose.slides/iimage/save/
---
## IImage::Save(System::String) मेथड

इमेज को फ़ाइल में सेव करता है।

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | वह पथ जहाँ इमेज को सेव किया जाएगा। |

## IImage::Save(System::String, ImageFormat) मेथड

इमेज को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सेव करता है।

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | वह पथ जहाँ इमेज को सेव किया जाएगा। |
| format | [ImageFormat](../../imageformat/) | इमेज का फ़ॉर्मेट। |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) मेथड

इमेज को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सेव करता है।

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वह स्ट्रीम जहाँ इमेज को सेव किया जाएगा। |
| format | [ImageFormat](../../imageformat/) | इमेज का फ़ॉर्मेट। |

## IImage::Save(System::String, ImageFormat, int32_t) मेथड

इमेज को निर्दिष्ट फ़ॉर्मेट और क्वालिटी में फ़ाइल में सेव करता है।

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | वह पथ जहाँ इमेज को सेव किया जाएगा। |
| format | [ImageFormat](../../imageformat/) | इमेज का फ़ॉर्मेट। |
| quality | **int32_t** | सेव की गई इमेज की क्वालिटी (0 से 100)। यह पैरामीटर केवल [ImageFormat::Jpeg](../../imageformat/) में सेव करने पर प्रभाव डालता है; अन्य सभी फ़ॉर्मेट्स के लिए इसे अनदेखा किया जाता है। |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) मेथड

इमेज को निर्दिष्ट फ़ॉर्मेट और क्वालिटी में स्ट्रीम में सेव करता है।

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वह स्ट्रीम जहाँ इमेज को सेव किया जाएगा। |
| format | [ImageFormat](../../imageformat/) | इमेज का फ़ॉर्मेट। |
| quality | **int32_t** | सेव की गई इमेज की क्वालिटी (0 से 100)। यह पैरामीटर केवल [ImageFormat::Jpeg](../../imageformat/) में सेव करने पर प्रभाव डालता है; अन्य सभी फ़ॉर्मेट्स के लिए इसे अनदेखा किया जाता है। |

## संबंधित देखें

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IImage](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)