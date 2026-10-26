---
title: ValidateElement()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान संदर्भ में तत्व को मान्य करता है।
type: docs
weight: 131
url: /hi/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) विधि

वर्तमान संदर्भ में तत्व को मान्य करता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | वैलिडेट करने के लिए तत्व का स्थानीय नाम। |
| namespaceUri | const [String](../../../system/string/)\& | वैलिडेट करने के लिए तत्व का नेमस्पेस URI। |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) ऑब्जेक्ट जिसका गुण तत्व के नाम के सफल वैलिडेशन पर सेट किया जाता है। यह पैरामीटर **nullptr** हो सकता है। |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) विधि

निर्दिष्ट **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, और **xsi:NoNamespaceSchemaLocation** एट्रीब्यूट मानों के साथ वर्तमान संदर्भ में तत्व को मान्य करता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | वैलिडेट करने के लिए तत्व का स्थानीय नाम। |
| namespaceUri | const [String](../../../system/string/)\& | वैलिडेट करने के लिए तत्व का नेमस्पेस URI। |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) ऑब्जेक्ट जिसका गुण तत्व के नाम के सफल वैलिडेशन पर सेट किया जाता है। यह पैरामीटर **nullptr** हो सकता है। |
| xsiType | const [String](../../../system/string/)\& | **xsi:Type** एट्रीब्यूट का मान। यह पैरामीटर **nullptr** हो सकता है। |
| xsiNil | const [String](../../../system/string/)\& | **xsi:Nil** एट्रीब्यूट का मान। यह पैरामीटर **nullptr** हो सकता है। |
| xsiSchemaLocation | const [String](../../../system/string/)\& | **xsi:SchemaLocation** एट्रीब्यूट का मान। यह पैरामीटर **nullptr** हो सकता है। |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | **xsi:NoNamespaceSchemaLocation** एट्रीब्यूट का मान। यह पैरामीटर **nullptr** हो सकता है। |

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [XmlSchemaInfo](../../xmlschemainfo/)
* क्लास [XmlSchemaValidator](../)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)