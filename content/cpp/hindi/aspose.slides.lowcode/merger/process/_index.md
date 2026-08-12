---
title: Process()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक ही स्वरूप की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।
type: docs
weight: 1
url: /hi/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) विधि

एक ही स्वरूप की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | इनपुट प्रस्तुति फ़ाइल नामों की एक एरे। |
| outputFileName | [System::String](../../../system/string/) | परिणामी मिलाए गए प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |

## टिप्पणियाँ

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) विधि

एक ही स्वरूप की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | इनपुट प्रस्तुति फ़ाइल नामों की एक एरे। |
| outputFileName | [System::String](../../../system/string/) | परिणामी मिलाए गए प्रस्तुति फ़ाइल का आउटपुट फ़ाइल नाम। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | विलयित प्रस्तुति को सहेजने के तरीके को परिभाषित करने वाले अतिरिक्त विकल्प। |

## टिप्पणियाँ

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) विधि

एक ही स्वरूप की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | इनपुट प्रस्तुति फ़ाइल नामों की एक एरे। |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | आउटपुट स्ट्रीम। |

## टिप्पणियाँ

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) विधि

एक ही स्वरूप की कई PowerPoint प्रस्तुतियों को एकल प्रस्तुति फ़ाइल में मिलाता है।

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | इनपुट प्रस्तुति फ़ाइल नामों की एक एरे। |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | आउटपुट स्ट्रीम। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | विलयित प्रस्तुति को सहेजने के तरीके को परिभाषित करने वाले अतिरिक्त विकल्प। |

## टिप्पणियाँ

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Merger](../)
* क्लास [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)