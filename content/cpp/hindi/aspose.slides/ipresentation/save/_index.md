---
title: Save()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉर्मेट के साथ प्रस्तुति की सभी स्लाइड्स को एक फ़ाइल में सहेजता है।
type: docs
weight: 404
url: /hi/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) मेथड

एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | निर्मित फ़ाइल का पथ। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) मेथड

एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | आउटपुट स्ट्रीम। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) मेथड

एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | निर्मित फ़ाइल का पथ। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | अतिरिक्त फ़ॉर्मेट विकल्प। |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) मेथड

एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | आउटपुट स्ट्रीम। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | अतिरिक्त फ़ॉर्मेट विकल्प। |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) मेथड

प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | निर्मित फ़ाइल का पथ। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) मेथड

प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | निर्मित फ़ाइल का पथ। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | अतिरिक्त फ़ॉर्मेट विकल्प। |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) मेथड

प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | आउटपुट स्ट्रीम। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) मेथड

प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट फ़ॉर्मेट और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | आउटपुट स्ट्रीम। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | अतिरिक्त फ़ॉर्मेट विकल्प। |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) मेथड

एक प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फ़ाइलों के सेट में सहेजता है।

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | XAML फ़ॉर्मेट विकल्प। |

## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## देखें

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IPresentation](../)
* Class [Stream](../../../system.io/stream/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)