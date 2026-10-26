---
title: Presentation()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह कन्स्ट्रक्टर शून्य से नई प्रस्तुति बनाता है। बनी प्रस्तुति में एक खाली स्लाइड होती है।
type: docs
weight: 417
url: /hi/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() निर्माता

यह निर्माता शून्य से नई प्रस्तुति बनाता है। बनी प्रस्तुति में एक खाली स्लाइड होती है।

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) निर्माता

यह निर्माता शून्य से नई प्रस्तुति बनाता है। बनी प्रस्तुति में एक खाली स्लाइड होती है।

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) निर्माता

यह निर्माता मौजूदा [Presentation](../) को पढ़ने के लिए प्राथमिक तंत्र है।

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | इनपुट स्ट्रीम। |

## टिप्पणियाँ

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) निर्माता

यह निर्माता मौजूदा [Presentation](../) को पढ़ने के लिए प्राथमिक तंत्र है।

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | इनपुट स्ट्रीम। |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | अतिरिक्त लोड विकल्प। |

## Presentation::Presentation(System::String) निर्माता

यह निर्माता एक स्रोत फ़ाइल पथ प्राप्त करता है जिससे [Presentation](../) की सामग्री पढ़ी जाती है।

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | इनपुट फ़ाइल। |

## टिप्पणियाँ

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) निर्माता

यह निर्माता एक स्रोत फ़ाइल पथ प्राप्त करता है जिससे [Presentation](../) की सामग्री पढ़ी जाती है।

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | इनपुट फ़ाइल। |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | अतिरिक्त लोड विकल्प। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Presentation](../)
* क्लास [LoadOptions](../../loadoptions/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)