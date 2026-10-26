---
title: GetAttribute()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम वाले एट्रिब्यूट का मान वापस करता है।
type: docs
weight: 443
url: /hi/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) मेथड

निर्दिष्ट नाम वाले एट्रीब्यूट का मान वापस करता है।

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रीब्यूट का क्वालिफाइड नाम। |

### रिटर्न वैल्यू

निर्दिष्ट एट्रीब्यूट का मान। यदि एट्रीब्यूट नहीं मिला, तो **nullptr** रिटर्न होता है।

## XmlValidatingReader::GetAttribute(String, String) मेथड

निर्दिष्ट स्थानीय नाम और नेमस्पेस यूनिफॉर्म रिसोर्स आइडेंटिफायर (URI) वाले एट्रीब्यूट का मान वापस करता है।

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रीब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रीब्यूट का नेमस्पेस URI। |

### रिटर्न वैल्यू

निर्दिष्ट एट्रीब्यूट का मान। यदि एट्रीब्यूट नहीं मिला, तो **nullptr** रिटर्न होता है। यह मेथड रीडर को नहीं बढ़ाता।

## XmlValidatingReader::GetAttribute(int32_t) मेथड

निर्दिष्ट इंडेक्स वाले एट्रीब्यूट का मान वापस करता है।

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| i | **int32_t** | एट्रीब्यूट का इंडेक्स। इंडेक्स शून्य-आधारित है। (पहला एट्रीब्यूट का इंडेक्स 0 है।) |

### रिटर्न वैल्यू

निर्दिष्ट एट्रीब्यूट का मान।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlValidatingReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)