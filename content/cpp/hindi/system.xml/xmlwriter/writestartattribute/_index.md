---
title: WriteStartAttribute()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्थानीय नाम और नेमस्पेस URI के साथ एक एट्रीब्यूट की शुरुआत लिखता है।
type: docs
weight: 144
url: /hi/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String&, const String&) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI के साथ एट्रीब्यूट की शुरुआत लिखता है।

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | एट्रीब्यूट का स्थानीय नाम। |
| ns | const [String](../../../system/string/)\& | एट्रीब्यूट का नेमस्पेस URI। |

## XmlWriter::WriteStartAttribute(const String&, const String&, const String&) विधि

जब डेराइव्ड क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट प्रीफ़िक्स, स्थानीय नाम और नेमस्पेस URI के साथ एट्रीब्यूट की शुरुआत लिखता है।

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | एट्रीब्यूट का नेमस्पेस प्रीफ़िक्स। |
| localName | const [String](../../../system/string/)\& | एट्रीब्यूट का स्थानीय नाम। |
| ns | const [String](../../../system/string/)\& | एट्रीब्यूट का नेमस्पेस URI। |

## XmlWriter::WriteStartAttribute(const String&) विधि

निर्दिष्ट स्थानीय नाम के साथ एट्रीब्यूट की शुरुआत लिखता है।

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | एट्रीब्यूट का स्थानीय नाम। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlWriter](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)