---
title: ValidateEndElement()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सरल सामग्री वाले तत्वों के लिए यह जांचता है कि तत्व की पाठ सामग्री उसके डेटा प्रकार के अनुसार मान्य है या नहीं, और जटिल सामग्री वाले तत्वों के लिए यह सत्यापित करता है कि वर्तमान तत्व की सामग्री पूर्ण है या नहीं।
type: docs
weight: 209
url: /hi/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) विधि

साधारण सामग्री वाले तत्वों के लिए तत्व की पाठ सामग्री डेटा प्रकार के अनुसार मान्य है या नहीं, तथा जटिल सामग्री वाले तत्वों के लिए वर्तमान तत्व की सामग्री पूरी है या नहीं, यह सत्यापित करता है।

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | एक [XmlSchemaInfo](../../xmlschemainfo/) ऑब्जेक्ट जिसका गुण तत्व के सफल सत्यापन पर सेट होते हैं। यह पैरामीटर **nullptr** हो सकता है। |

### रिटर्न वैल्यू

यदि तत्व में साधारण सामग्री है तो तत्व का पार्स किया हुआ, टाइप किया गया पाठ मान।

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) विधि

निर्दिष्ट तत्व की पाठ सामग्री डेटा प्रकार के अनुसार वैध है या नहीं, यह सत्यापित करता है।

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | एक [XmlSchemaInfo](../../xmlschemainfo/) ऑब्जेक्ट जिसका गुण तत्व की पाठ सामग्री के सफल सत्यापन पर सेट होते हैं। यह पैरामीटर **nullptr** हो सकता है। |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | तत्व की टाइप की गई पाठ सामग्री। |

### रिटर्न वैल्यू

तत्व की पार्स की गई, टाइप की गई साधारण सामग्री।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [XmlSchemaInfo](../../xmlschemainfo/)
* क्लास [XmlSchemaValidator](../)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)