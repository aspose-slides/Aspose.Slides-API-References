---
title: Create()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ाइलनाम का उपयोग करके नया XmlWriter इंस्टेंस बनाता है।
type: docs
weight: 469
url: /hi/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) विधि

निर्दिष्ट फ़ाइलनाम का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | फ़ाइल जिसमें आप लिखना चाहते हैं। [XmlWriter](../) निर्दिष्ट पथ पर एक फ़ाइल बनाता है और उसे XML 1.0 टेक्स्ट सिंटैक्स में लिखता है। **outputFileName** एक फ़ाइल सिस्टम पथ होना चाहिए। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) विधि

फ़ाइलनाम और [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | फ़ाइल जिसमें आप लिखना चाहते हैं। [XmlWriter](../) निर्दिष्ट पथ पर एक फ़ाइल बनाता है और उसे XML 1.0 टेक्स्ट सिंटैक्स में लिखता है। **outputFileName** एक फ़ाइल सिस्टम पथ होना चाहिए। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | नया [XmlWriter](../) इंस्टेंस कॉन्फ़िगर करने के लिए उपयोग किया गया [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट। यदि यह **nullptr** है, तो डिफ़ॉल्ट सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) उपयोग किया जाता है। यदि [XmlWriter](../) को XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) विधि के साथ उपयोग किया जा रहा है, तो आपको XslCompiledTransform::get_OutputSettings मान का उपयोग करके सही सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट प्राप्त करना चाहिए। इससे यह सुनिश्चित होता है कि निर्मित [XmlWriter](../) ऑब्जेक्ट के पास सही आउटपुट सेटिंग्स हों। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) विधि

निर्दिष्ट स्ट्रीम का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें आप लिखना चाहते हैं। [XmlWriter](../) XML 1.0 टेक्स्ट सिंटैक्स लिखता है और उसे निर्दिष्ट स्ट्रीम में जोड़ता है। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) विधि

स्ट्रीम और [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें आप लिखना चाहते हैं। [XmlWriter](../) XML 1.0 टेक्स्ट सिंटैक्स लिखता है और उसे निर्दिष्ट स्ट्रीम में जोड़ता है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | नया [XmlWriter](../) इंस्टेंस कॉन्फ़िगर करने के लिए उपयोग किया गया [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट। यदि यह **nullptr** है, तो डिफ़ॉल्ट सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) उपयोग किया जाता है। यदि [XmlWriter](../) को XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) विधि के साथ उपयोग किया जा रहा है, तो आपको XslCompiledTransform::get_OutputSettings मान का उपयोग करके सही सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट प्राप्त करना चाहिए। इससे यह सुनिश्चित होता है कि निर्मित [XmlWriter](../) ऑब्जेक्ट के पास सही आउटपुट सेटिंग्स हों। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) विधि

निर्दिष्ट TextWriter का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | वह TextWriter जिसमें आप लिखना चाहते हैं। [XmlWriter](../) XML 1.0 टेक्स्ट सिंटैक्स लिखता है और उसे निर्दिष्ट TextWriter में जोड़ता है। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) विधि

TextWriter और [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | वह TextWriter जिसमें आप लिखना चाहते हैं। [XmlWriter](../) XML 1.0 टेक्स्ट सिंटैक्स लिखता है और उसे निर्दिष्ट TextWriter में जोड़ता है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | नया [XmlWriter](../) इंस्टेंस कॉन्फ़िगर करने के लिए उपयोग किया गया [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट। यदि यह **nullptr** है, तो डिफ़ॉल्ट सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) उपयोग किया जाता है। यदि [XmlWriter](../) को XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) विधि के साथ उपयोग किया जा रहा है, तो आपको XslCompiledTransform::get_OutputSettings मान का उपयोग करके सही सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट प्राप्त करना चाहिए। इससे यह सुनिश्चित होता है कि निर्मित [XmlWriter](../) ऑब्जेक्ट के पास सही आउटपुट सेटिंग्स हों। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) विधि

निर्दिष्ट [Text::StringBuilder](../../../system.text/stringbuilder/) का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | वह [Text::StringBuilder](../../../system.text/stringbuilder/) जिसमें लिखना है। [XmlWriter](../) द्वारा लिखा गया कंटेंट [Text::StringBuilder](../../../system.text/stringbuilder/) में जोड़ा जाता है। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) विधि

[Text::StringBuilder](../../../system.text/stringbuilder/) और [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | वह [Text::StringBuilder](../../../system.text/stringbuilder/) जिसमें लिखना है। [XmlWriter](../) द्वारा लिखा गया कंटेंट [Text::StringBuilder](../../../system.text/stringbuilder/) में जोड़ा जाता है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | नया [XmlWriter](../) इंस्टेंस कॉन्फ़िगर करने के लिए उपयोग किया गया [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट। यदि यह **nullptr** है, तो डिफ़ॉल्ट सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) उपयोग किया जाता है। यदि [XmlWriter](../) को XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) विधि के साथ उपयोग किया जा रहा है, तो आपको XslCompiledTransform::get_OutputSettings मान का उपयोग करके सही सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट प्राप्त करना चाहिए। इससे यह सुनिश्चित होता है कि निर्मित [XmlWriter](../) ऑब्जेक्ट के पास सही आउटपुट सेटिंग्स हों। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट।

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) विधि

निर्दिष्ट [XmlWriter](../) ऑब्जेक्ट का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | वह [XmlWriter](../) ऑब्जेक्ट जिसे आप आधार लेखक के रूप में उपयोग करना चाहते हैं। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट जो निर्दिष्ट [XmlWriter](../) ऑब्जेक्ट के चारों ओर रैप किया गया है।

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) विधि

निर्दिष्ट [XmlWriter](../) और [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके नया [XmlWriter](../) इंस्टेंस बनाता है।

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | वह [XmlWriter](../) ऑब्जेक्ट जिसे आप आधार लेखक के रूप में उपयोग करना चाहते हैं। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | नया [XmlWriter](../) इंस्टेंस कॉन्फ़िगर करने के लिए उपयोग किया गया [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट। यदि यह **nullptr** है, तो डिफ़ॉल्ट सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) उपयोग किया जाता है। यदि [XmlWriter](../) को XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) विधि के साथ उपयोग किया जा रहा है, तो आपको XslCompiledTransform::get_OutputSettings मान का उपयोग करके सही सेटिंग्स वाला एक [XmlWriterSettings](../../xmlwritersettings/) ऑब्जेक्ट प्राप्त करना चाहिए। इससे यह सुनिश्चित होता है कि निर्मित [XmlWriter](../) ऑब्जेक्ट के पास सही आउटपुट सेटिंग्स हों। |

### वापसी मान

एक [XmlWriter](../) ऑब्जेक्ट जो निर्दिष्ट [XmlWriter](../) ऑब्जेक्ट के चारों ओर रैप किया गया है।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlWriter](../)
* क्लास [String](../../../system/string/)
* क्लास [XmlWriterSettings](../../xmlwritersettings/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [TextWriter](../../../system.io/textwriter/)
* क्लास [StringBuilder](../../../system.text/stringbuilder/)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)