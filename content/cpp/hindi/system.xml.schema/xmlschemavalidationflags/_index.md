---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlSchemaValidator और XmlReader वर्गों द्वारा उपयोग किए जाने वाले स्कीमा वैलिडेशन विकल्पों को निर्दिष्ट करता है।
type: docs
weight: 1054
url: /hi/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

schema validation विकल्पों को निर्दिष्ट करता है जो [XmlSchemaValidator](../xmlschemavalidator/) और [XmlReader](../../system.xml/xmlreader/) वर्गों द्वारा उपयोग किए जाते हैं।

```cpp
enum class XmlSchemaValidationFlags
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | पहचान बाधाओं, इनलाइन स्कीमा, स्कीमा लोकेशन संकेतों को प्रोसेस न करें, या स्कीमा वैलिडेशन चेतावनियों की रिपोर्ट न करें। |
| ProcessInlineSchema | 1 | जांच के दौरान मिलने वाले इनलाइन स्कीमा को प्रोसेस करें। |
| ProcessSchemaLocation | 2 | जांच के दौरान मिलने वाले स्कीमा लोकेशन संकेतों (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) को प्रोसेस करें। |
| ReportValidationWarnings | 4 | जांच के दौरान मिलने वाली स्कीमा वैलिडेशन चेतावनियों की रिपोर्ट करें। |
| ProcessIdentityConstraints | 8 | जांच के दौरान मिलने वाली पहचान बाधाओं (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) को प्रोसेस करें। |
| AllowXmlAttributes | 16 | xml:* गुणधर्मों को अनुमति दें भले ही वे स्कीमा में परिभाषित न हों। इन गुणधर्मों को उनके डेटा प्रकार के आधार पर वैलिडेट किया जाएगा। |

## देखें

* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)