---
title: CheckValidity()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सत्यापित करता है कि XPathNavigator में XML डेटा प्रदान किए गए XML Schema परिभाषा भाषा (XSD) स्कीमा के अनुरूप है।
type: docs
weight: 755
url: /hi/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method

सत्यापित करता है कि [XPathNavigator](../) में XML डेटा प्रदान किए गए XML [Schema](../../../system.xml.schema/) परिभाषा भाषा (XSD) स्कीमा के अनुरूप है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### आर्ग्युमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | [XPathNavigator](../) में मौजूद XML डेटा को मान्य करने के लिए प्रयुक्त स्कीमा को सम्मिलित करने वाला XmlSchemaSet। |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | स्कीमा मान्यकरण चेतावनियों और त्रुटियों के बारे में जानकारी प्राप्त करने वाला ValidationEventHandler। |

### रिटर्न मान

**true** यदि कोई स्कीमा मान्यकरण त्रुटि नहीं हुई; अन्यथा, **false**।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)