---
title: ValidationType
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: किया जाने वाला सत्यापन का प्रकार निर्दिष्ट करता है।
type: docs
weight: 729
url: /hi/system.xml/validationtype/
---
## ValidationType enum

Specifies the type of validation to perform.

```cpp
enum class ValidationType
```

### Values

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | No validation is performed, and no validation errors are thrown. This setting creates an XML 1.0 compliant non-validating parser. |
| Auto | 1 | यदि DTD या स्कीमा जानकारी मिलती है तो वैध करता है। |
| DTD | 2 | DTD के अनुसार वैध करता है। |
| XDR | 3 | XML-Data Reduced (XDR) स्कीमा के अनुसार वैध करें, जिसमें inline XDR स्कीमा शामिल हैं। XDR स्कीमा को **x-schema** namespace उपसर्ग या [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) मान का उपयोग करके पहचाना जाता है। |
| Schema | 4 | XML [Schema](../../system.xml.schema/) definition language (XSD) स्कीमा के अनुसार वैध करें, जिसमें inline XML Schemas शामिल हैं। XML Schemas को namespace URIs के साथ या तो **schemaLocation** विशेषता का उपयोग करके या प्रदान किए गए **Schemas** द्वारा जुड़ा जाता है। |

## देखें

* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)