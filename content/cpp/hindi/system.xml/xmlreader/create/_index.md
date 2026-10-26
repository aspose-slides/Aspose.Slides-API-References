---
title: Create()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट URI के साथ एक नया XmlReader इंस्टेंस बनाता है।
type: docs
weight: 1015
url: /hi/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) विधि

निर्दिष्ट URI के साथ नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | फ़ाइल का URI जो XML डेटा रखती है। [XmlUrlResolver](../../xmlurlresolver/) क्लास का उपयोग पथ को एक मानक डेटा प्रतिनिधित्व में बदलने के लिए किया जाता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) विधि

निर्दिष्ट URI और सेटिंग्स का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | फ़ाइल का URI जिसमें XML डेटा है। [XmlReaderSettings](../../xmlreadersettings/) ऑब्जेक्ट पर स्थित [XmlResolver](../../xmlresolver/) ऑब्जेक्ट पथ को एक मानक डेटा प्रतिनिधित्व में बदलने के लिए उपयोग किया जाता है। यदि XmlReaderSettings::get_XmlResolver का मान **nullptr** है, तो नया [XmlUrlResolver](../../xmlurlresolver/) ऑब्जेक्ट उपयोग किया जाता है। |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) विधि

निर्दिष्ट URI, सेटिंग्स और पार्सिंग के लिए कॉन्टेक्स्ट जानकारी का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | फ़ाइल का URI जिसमें XML डेटा है। [XmlReaderSettings](../../xmlreadersettings/) ऑब्जेक्ट पर स्थित [XmlResolver](../../xmlresolver/) ऑब्जेक्ट पथ को एक मानक डेटा प्रतिनिधित्व में बदलने के लिए उपयोग किया जाता है। यदि XmlReaderSettings::get_XmlResolver का मान **nullptr** है, तो नया [XmlUrlResolver](../../xmlurlresolver/) ऑब्जेक्ट उपयोग किया जाता है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML फ्रैगमेंट को पार्स करने के लिए आवश्यक संदर्भ जानकारी। संदर्भ जानकारी में उपयोग करने के लिए [XmlNameTable](../../xmlnametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang** और **xml:space** स्कोप, बेस URI, और दस्तावेज़ प्रकार परिभाषा शामिल हो सकती है। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) विधि

डिफ़ॉल्ट सेटिंग्स के साथ निर्दिष्ट स्ट्रीम का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें XML डेटा है। [XmlReader](../) स्ट्रीम के पहले बाइट्स को स्कैन करता है ताकि बाइट ऑर्डर मार्क या अन्य एन्कोडिंग संकेत मिल सके। एन्कोडिंग निर्धारित होने पर, उसी एन्कोडिंग का उपयोग स्ट्रीम को पढ़ने के लिए किया जाता है, और प्रोसेसिंग (Unicode) अक्षरों की स्ट्रीम के रूप में इनपुट को पार्स करती रहती है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) विधि

निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें XML डेटा है। [XmlReader](../) स्ट्रीम के पहले बाइट्स को स्कैन करता है ताकि बाइट ऑर्डर मार्क या अन्य एन्कोडिंग संकेत मिल सके। एन्कोडिंग निर्धारित होने पर, उसी एन्कोडिंग का उपयोग स्ट्रीम को पढ़ने के लिए किया जाता है, और प्रोसेसिंग (Unicode) अक्षरों की स्ट्रीम के रूप में इनपुट को पार्स करती रहती है। |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) विधि

निर्दिष्ट स्ट्रीम, बेस URI और सेटिंग्स का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें XML डेटा है। [XmlReader](../) स्ट्रीम के पहले बाइट्स को स्कैन करता है ताकि बाइट ऑर्डर मार्क या अन्य एन्कोडिंग संकेत मिल सके। एन्कोडिंग निर्धारित होने पर, उसी एन्कोडिंग का उपयोग स्ट्रीम को पढ़ने के लिए किया जाता है, और प्रोसेसिंग (Unicode) अक्षरों की स्ट्रीम के रूप में इनपुट को पार्स करती रहती है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |
| baseUri | const [String](../../../system/string/)\& | पढ़ी जा रही इकाई या दस्तावेज़ के लिए बेस URI। यह मान **nullptr** हो सकता है। **[Security](../../../system.security/) नोट** बेस URI का उपयोग XML दस्तावेज़ के सापेक्ष URI को हल करने के लिये किया जाता है। अप्रविश्वसनीय स्रोत से बेस URI का उपयोग न करें। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) विधि

निर्दिष्ट स्ट्रीम, सेटिंग्स और पार्सिंग के लिए कॉन्टेक्स्ट जानकारी का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | वह स्ट्रीम जिसमें XML डेटा है। [XmlReader](../) स्ट्रीम के पहले बाइट्स को स्कैन करता है ताकि बाइट ऑर्डर मार्क या अन्य एन्कोडिंग संकेत मिल सके। एन्कोडिंग निर्धारित होने पर, उसी एन्कोडिंग का उपयोग स्ट्रीम को पढ़ने के लिए किया जाता है, और प्रोसेसिंग (Unicode) अक्षरों की स्ट्रीम के रूप में इनपुट को पार्स करती रहती है। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML फ्रैगमेंट को पार्स करने के लिए आवश्यक संदर्भ जानकारी। संदर्भ जानकारी में उपयोग करने के लिए [XmlNameTable](../../xmlnametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang** और **xml:space** स्कोप, बेस URI, और दस्तावेज़ प्रकार परिभाषा शामिल हो सकती है। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) विधि

निर्दिष्ट टेक्स्ट रीडर का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | वह टेक्स्ट रीडर जिससे XML डेटा पढ़ा जाता है। टेक्स्ट रीडर यूनिकोड अक्षरों की स्ट्रीम लौटाता है, इसलिए XML घोषणा में निर्दिष्ट एन्कोडिंग XML रीडर द्वारा डेटा स्ट्रीम को डिकोड करने के लिए उपयोग नहीं की जाती। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) विधि

निर्दिष्ट टेक्स्ट रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | वह टेक्स्ट रीडर जिससे XML डेटा पढ़ा जाता है। टेक्स्ट रीडर यूनिकोड अक्षरों की स्ट्रीम लौटाता है, इसलिए XML घोषणा में निर्दिष्ट एन्कोडिंग XML रीडर द्वारा डेटा स्ट्रीम को डिकोड करने के लिए उपयोग नहीं की जाती। |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | नए [XmlReader](../) के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) विधि

निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और बेस URI का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | वह टेक्स्ट रीडर जिससे XML डेटा पढ़ा जाता है। टेक्स्ट रीडर यूनिकोड अक्षरों की स्ट्रीम लौटाता है, इसलिए XML घोषणा में निर्दिष्ट एन्कोडिंग [XmlReader](../) द्वारा डेटा स्ट्रीम को डिकोड करने के लिए उपयोग नहीं की जाती। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |
| baseUri | const [String](../../../system/string/)\& | पढ़ी जा रही इकाई या दस्तावेज़ के लिए बेस URI। यह मान **nullptr** हो सकता है। **[Security](../../../system.security/) नोट** बेस URI का उपयोग XML दस्तावेज़ के सापेक्ष URI को हल करने के लिये किया जाता है। अप्रविश्वसनीय स्रोत से बेस URI का उपयोग न करें। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) विधि

निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और पार्सिंग के लिए कॉन्टेक्स्ट जानकारी का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | वह टेक्स्ट रीडर जिससे XML डेटा पढ़ा जाता है। टेक्स्ट रीडर यूनिकोड अक्षरों की स्ट्रीम लौटाता है, इसलिए XML घोषणा में निर्दिष्ट एन्कोडिंग XML रीडर द्वारा डेटा स्ट्रीम को डिकोड करने के लिए उपयोग नहीं की जाती। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। यह मान **nullptr** हो सकता है। |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML फ्रैगमेंट को पार्स करने के लिए आवश्यक संदर्भ जानकारी। संदर्भ जानकारी में उपयोग करने के लिए [XmlNameTable](../../xmlnametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang** और **xml:space** स्कोप, बेस URI, और दस्तावेज़ प्रकार परिभाषा शामिल हो सकती है। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

एक ऑब्जेक्ट जिसे स्ट्रीम में XML डेटा पढ़ने के लिए उपयोग किया जाता है।

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) विधि

निर्दिष्ट XML रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](../) उदाहरण बनाता है।

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | वह ऑब्जेक्ट जिसे आप आधारभूत XML रीडर के रूप में उपयोग करना चाहते हैं। |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | नए [XmlReader](../) उदाहरण के लिए सेटिंग्स। [XmlReaderSettings](../../xmlreadersettings/) ऑब्जेक्ट का कन्फॉर्मेंस लेवल या तो आधारभूत रीडर के कन्फॉर्मेंस लेवल से मेल खाना चाहिए, या इसे [ConformanceLevel::Auto](../../conformancelevel/) पर सेट किया जाना चाहिए। |

### रिटर्न मान

निर्दिष्ट [XmlReader](../) ऑब्जेक्ट के चारों ओर लपटा गया एक ऑब्जेक्ट।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)