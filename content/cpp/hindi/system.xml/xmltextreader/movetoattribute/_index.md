---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है।
type: docs
weight: 508
url: /hi/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) मेथड

निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है।

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का योग्य नाम। |

### रिटर्न वैल्यू

**true** यदि एट्रिब्यूट पाया जाता है; अन्यथा **false**। यदि **false**, तो रीडर की स्थिति नहीं बदलती।

## XmlTextReader::MoveToAttribute(String, String) मेथड

निर्दिष्ट लोकल नाम और नेमस्पेस URI वाले एट्रिब्यूट पर जाता है।

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रिब्यूट का लोकल नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न वैल्यू

**true** यदि एट्रिब्यूट पाया जाता है; अन्यथा **false**। यदि **false**, तो रीडर की स्थिति नहीं बदलती।

## XmlTextReader::MoveToAttribute(int32_t) मेथड

निर्दिष्ट इंडेक्स वाले एट्रिब्यूट पर जाता है।

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **int32_t** | एट्रिब्यूट का इंडेक्स। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)