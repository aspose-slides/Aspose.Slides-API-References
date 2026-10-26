---
title: get_ValidationFlags()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "स्कीमा वैधता सेटिंग्स को दर्शाने वाला एक मान लौटाता है। यह सेटिंग उन XmlReader ऑब्जेक्ट्स पर लागू होती है जो स्कीमा को मान्य करते हैं (XmlReaderSettings::get_ValidationType मान है ValidationType::Schema)।"
type: docs
weight: 378
url: /hi/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() विधि

स्कीमा वैधता सेटिंग्स को दर्शाने वाला एक मूल्य लौटाता है। यह सेटिंग [XmlReader](../../xmlreader/) ऑब्जेक्ट्स पर लागू होती है जो स्कीमा को मान्य करते हैं ([XmlReaderSettings::get_ValidationType](../get_validationtype/) मूल्य है [ValidationType::Schema](../../validationtype/))।

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### वापसी मान

वैलिडेशन विकल्पों को निर्दिष्ट करने वाले enumeration मानों का बिटवाइज़ संयोजन। XmlSchemaValidationFlags::ProcessIdentityConstraints और XmlSchemaValidationFlags::AllowXmlAttributes डिफ़ॉल्ट रूप से सक्षम हैं। XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation और XmlSchemaValidationFlags::ReportValidationWarnings डिफ़ॉल्ट रूप से निष्क्रिय हैं।

## संबंधित देखें

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* क्लास [XmlReaderSettings](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)