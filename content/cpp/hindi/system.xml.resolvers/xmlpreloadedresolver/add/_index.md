---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बाइट ऐरे को XmlPreloadedResolver स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए मैपिंग मौजूद है, तो मौजूदा मैपिंग को ओवरराइड कर दिया जाता है।
type: docs
weight: 79
url: /hi/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) मेथड

एक बाइट ऐरे को [XmlPreloadedResolver](../) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए मैपिंग मौजूद है, तो मौजूदा मैपिंग को ओवरराइड कर दिया जाता है।

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | डेटा का URI जो [XmlPreloadedResolver](../) स्टोर में जोड़ा जा रहा है। |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एक बाइट ऐरे जिसमें वह डेटा है जो प्रदान किए गए URI से संबंधित है। |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) मेथड

एक बाइट ऐरे को [XmlPreloadedResolver](../) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए मैपिंग मौजूद है, तो मौजूदा मैपिंग को ओवरराइड कर दिया जाता है।

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | डेटा का URI जो [XmlPreloadedResolver](../) स्टोर में जोड़ा जा रहा है। |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | एक बाइट ऐरे जिसमें वह डेटा है जो प्रदान किए गए URI से संबंधित है। |
| offset | **int32_t** | प्रदान किए गए बाइट ऐरे में वह ऑफसेट जहाँ डेटा शुरू होता है। |
| count | **int32_t** | बाइट ऐरे से पढ़े जाने वाले बाइट्स की संख्या, जो प्रदान किए गए ऑफसेट से शुरू होती है। |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) मेथड

एक Stream को [XmlPreloadedResolver](../) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए मैपिंग मौजूद है, तो मौजूदा मैपिंग को ओवरराइड कर दिया जाता है।

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | डेटा का URI जो [XmlPreloadedResolver](../) स्टोर में जोड़ा जा रहा है। |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | एक Stream जिसमें वह डेटा है जो प्रदान किए गए URI से संबंधित है। |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) मेथड

एक स्ट्रिंग को [XmlPreloadedResolver](../) स्टोर में पहले से लोडेड डेटा के साथ जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए मैपिंग मौजूद है, तो मौजूदा मैपिंग को ओवरराइड कर दिया जाता है।

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | डेटा का URI जो [XmlPreloadedResolver](../) स्टोर में जोड़ा जा रहा है। |
| value | const [String](../../../system/string/)\& | एक [String](../../../system/string/) जिसमें वह डेटा है जो प्रदान किए गए URI से संबंधित है। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [XmlPreloadedResolver](../)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [String](../../../system/string/)
* नामस्थान [System::Xml::Resolvers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)