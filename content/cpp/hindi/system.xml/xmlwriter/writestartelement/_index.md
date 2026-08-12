---
title: WriteStartElement()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट प्रारंभ टैग लिखता है और इसे दिए गए नामस्थान से जोड़ता है।
type: docs
weight: 92
url: /hi/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) मेथड

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट प्रारंभ टैग लिखता है और इसे दिए गए नामस्थान से जोड़ता है।

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | तत्व का स्थानीय नाम। |
| ns | const [String](../../../system/string/)\& | तत्व के साथ जुड़ने वाला नामस्थान URI। यदि यह नामस्थान पहले से ही दायरे में है और इसका एक संबद्ध उपसर्ग है, तो राइटर स्वतः वह उपसर्ग भी लिख देता है। |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) मेथड

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट प्रारंभ टैग लिखता है और इसे दिए गए नामस्थान और उपसर्ग से जोड़ता है।

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | तत्व का नामस्थान उपसर्ग। |
| localName | const [String](../../../system/string/)\& | तत्व का स्थानीय नाम। |
| ns | const [String](../../../system/string/)\& | तत्व के साथ जुड़ने वाला नामस्थान URI। |

## XmlWriter::WriteStartElement(const String\&) मेथड

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट स्थानीय नाम के साथ एक प्रारंभ टैग लिखता है।

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | तत्व का स्थानीय नाम। |

## संबंधित देखें

* वर्ग [String](../../../system/string/)
* वर्ग [XmlWriter](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)