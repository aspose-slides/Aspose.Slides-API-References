---
title: ToDateTimeOffset()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रदान किए गए String को DateTimeOffset समकक्ष में परिवर्तित करता है।
type: docs
weight: 430
url: /hi/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) मेथड

प्रदान किए गए [String](../../../system/string/) को [DateTimeOffset](../../../system/datetimeoffset/) समकक्ष में परिवर्तित करता है।

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिये स्ट्रिंग। स्ट्रिंग को XML dateTime प्रकार के लिए W3C Recommendation के एक उपसमुच्चय के अनुरूप होना चाहिए। अधिक जानकारी के लिये, XML [Schema](../../../system.xml.schema/) विनिर्देशन के [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) अनुभाग देखें। |

### रिटर्न वैल्यू

प्रदान की गई स्ट्रिंग का [DateTimeOffset](../../../system/datetimeoffset/) समकक्ष।

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) मेथड

प्रदान किए गए [String](../../../system/string/) को [DateTimeOffset](../../../system/datetimeoffset/) समकक्ष में परिवर्तित करता है।

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिये स्ट्रिंग। |
| format | const [String](../../../system/string/)\& | फ़ॉर्मेट जिससे **s** को परिवर्तित किया जाता है। फ़ॉर्मेट पैरामीटर XML dateTime प्रकार के W3C Recommendation के किसी भी उपसमुच्चय हो सकता है। अधिक जानकारी के लिये, XML [Schema](../../../system.xml.schema/) विनिर्देशन के [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) अनुभाग देखें। स्ट्रिंग **s** को इस फ़ॉर्मेट के विरुद्ध जांचा जाता है। |

### रिटर्न वैल्यू

प्रदान की गई स्ट्रिंग का [DateTimeOffset](../../../system/datetimeoffset/) समकक्ष।

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) मेथड

प्रदान किए गए [String](../../../system/string/) को [DateTimeOffset](../../../system/datetimeoffset/) समकक्ष में परिवर्तित करता है।

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिये स्ट्रिंग। |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | फ़ॉर्मेट्स की एक एरे जिससे **s** को परिवर्तित किया जा सकता है। **formats** में प्रत्येक फ़ॉर्मेट XML dateTime प्रकार के W3C Recommendation के किसी भी उपसमुच्चय हो सकता है। अधिक जानकारी के लिये, XML [Schema](../../../system.xml.schema/) विनिर्देशन के [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) अनुभाग देखें। स्ट्रिंग **s** को इन फ़ॉर्मेट्स में से किसी एक के विरुद्ध जांचा जाता है। |

### रिटर्न वैल्यू

प्रदान की गई स्ट्रिंग का [DateTimeOffset](../../../system/datetimeoffset/) समकक्ष।

## देखें भी

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [DateTimeOffset](../../../system/datetimeoffset/)
* क्लास [String](../../../system/string/)
* क्लास [XmlConvert](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)