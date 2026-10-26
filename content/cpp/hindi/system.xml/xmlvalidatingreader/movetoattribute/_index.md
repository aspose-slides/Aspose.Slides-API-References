---
title: MoveToAttribute()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है।
type: docs
weight: 456
url: /hi/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) मेथड

निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है।

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का योग्य नाम। |

### रिटर्न वैल्यू

**true** यदि एट्रिब्यूट मिला है; अन्यथा **false**। यदि **false**, रीडर की स्थिति नहीं बदलती।

## XmlValidatingReader::MoveToAttribute(String, String) मेथड

निर्दिष्ट स्थानीय नाम और नेमस्पेस यूनिफॉर्म रिसोर्स आइडेंटिफायर (URI) वाले एट्रिब्यूट पर आता है।

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न वैल्यू

**true** यदि एट्रिब्यूट मिला है; अन्यथा **false**। यदि **false**, रीडर की स्थिति नहीं बदलती।

## XmlValidatingReader::MoveToAttribute(int32_t) मेथड

निर्दिष्ट सूचकांक वाला एट्रिब्यूट पर जाता है।

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| i | **int32_t** | एट्रिब्यूट का सूचकांक। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlValidatingReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)