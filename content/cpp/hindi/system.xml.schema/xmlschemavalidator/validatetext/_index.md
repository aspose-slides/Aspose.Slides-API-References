---
title: ValidateText()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि निर्दिष्ट पाठ स्ट्रिंग वर्तमान तत्व संदर्भ में अनुमत है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो सत्यापन के लिये पाठ को संकलित करता है।
type: docs
weight: 183
url: /hi/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) विधि


यह सत्यापित करता है कि निर्दिष्ट **string** वर्तमान तत्व संदर्भ में अनुमत है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो सत्यापन के लिए पाठ को संग्रहीत करता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | वर्तमान तत्व संदर्भ में सत्यापन के लिये एक पाठ **string**। |

## XmlSchemaValidator::ValidateText(XmlValueGetter) विधि


यह सत्यापित करता है कि निर्दिष्ट XmlValueGetter वस्तु द्वारा लौटाया गया पाठ वर्तमान तत्व संदर्भ में अनुमत है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो सत्यापन के लिए पाठ को संग्रहीत करता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | एक XmlValueGetter कॉलबैक जिसका उपयोग पाठ मान को XML [Schema](../../) परिभाषा भाषा (XSD) प्रकार के अनुरूप के रूप में, विशेषता के लिये पास करने हेतु किया जाता है। |

## देखिए

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)