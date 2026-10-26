---
title: ValidateAttribute()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान तत्व संदर्भ में एट्रीब्यूट का नाम, नेमस्पेस URI, और मान को सत्यापित करता है।
type: docs
weight: 144
url: /hi/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) मेथड

वर्तमान तत्व संदर्भ में एट्रीब्यूट का नाम, नेमस्पेस URI, और मान को सत्यापित करता है।

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | सत्यापित करने के लिए एट्रीब्यूट का स्थानीय नाम। |
| namespaceUri | const [String](../../../system/string/)\& | सत्यापित करने के लिए एट्रीब्यूट का नेमस्पेस URI। |
| attributeValue | const [String](../../../system/string/)\& | सत्यापित करने के लिए एट्रीब्यूट का मान। |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | एक [XmlSchemaInfo](../../xmlschemainfo/) ऑब्जेक्ट जिसकी प्रॉपर्टीज़ एट्रीब्यूट के सफल सत्यापन पर सेट की जाती हैं। यह पैरामीटर **nullptr** हो सकता है। |

### रिटर्न वैल्यू

सत्यापित एट्रीब्यूट का मान।

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) मेथड

वर्तमान तत्व संदर्भ में एट्रीब्यूट का नाम, नेमस्पेस URI, और मान को सत्यापित करता है।

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | सत्यापित करने के लिए एट्रीब्यूट का स्थानीय नाम। |
| namespaceUri | const [String](../../../system/string/)\& | सत्यापित करने के लिए एट्रीब्यूट का नेमस्पेस URI। |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | एट्रीब्यूट के मान को XML [Schema](../../) डेफ़िनिशन लैंग्वेज (XSD) प्रकार के साथ संगत प्रकार में पास करने के लिए उपयोग किया जाने वाला XmlValueGetter कॉलबैक। |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | एक [XmlSchemaInfo](../../xmlschemainfo/) ऑब्जेक्ट जिसकी प्रॉपर्टीज़ एट्रीब्यूट के सफल सत्यापन पर सेट की जाती हैं। यह पैरामीटर **nullptr** हो सकता है। |

### रिटर्न वैल्यू

सत्यापित एट्रीब्यूट का मान।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* क्लास [Object](../../../system/object/)
* क्लास [String](../../../system/string/)
* क्लास [XmlSchemaInfo](../../xmlschemainfo/)
* क्लास [XmlSchemaValidator](../)
* नामस्थान [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)