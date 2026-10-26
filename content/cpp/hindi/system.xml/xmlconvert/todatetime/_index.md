---
title: ToDateTime()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: String को DateTime के समतुल्य में परिवर्तित करता है।
type: docs
weight: 417
url: /hi/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) विधि

[String](../../../system/string/) को [DateTime](../../../system/datetime/) के समतुल्य में परिवर्तित करता है।

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |

### वापसी मान

स्ट्रिंग का [DateTime](../../../system/datetime/) समतुल्य।

## XmlConvert::ToDateTime(const String\&, const String\&) विधि

[String](../../../system/string/) को [DateTime](../../../system/datetime/) के समतुल्य में परिवर्तित करता है।

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| format | const [String](../../../system/string/)\& | परिवर्तित [DateTime](../../../system/datetime/) पर लागू करने के लिए स्वरूप संरचना। मान्य स्वरूपों में "yyyy-MM-ddTHH:mm:sszzzzzz" और इसके उपसमुच्चय शामिल हैं। स्ट्रिंग को इस स्वरूप के विरुद्ध मान्य किया जाता है। |

### वापसी मान

स्ट्रिंग का [DateTime](../../../system/datetime/) समतुल्य।

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) विधि

[String](../../../system/string/) को [DateTime](../../../system/datetime/) के समतुल्य में परिवर्तित करता है।

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिए स्ट्रिंग। |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | परिवर्तित [DateTime](../../../system/datetime/) पर लागू करने के लिए स्वरूप संरचनाएँ शामिल करने वाला एक एरे। मान्य स्वरूपों में "yyyy-MM-ddTHH:mm:sszzzzzz" और इसके उपसमुच्चय शामिल हैं। |

### वापसी मान

स्ट्रिंग का [DateTime](../../../system/datetime/) समतुल्य।

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) विधि

[String](../../../system/string/) को [DateTime](../../../system/datetime/) का उपयोग करके XmlDateTimeSerializationMode द्वारा निर्दिष्ट किया गया।

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | परिवर्तित करने के लिए [String](../../../system/string/) मान। |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | एक ईन्यूमरेशन मूल्य जो निर्धारित करता है कि यदि यह UTC तिथि है तो तिथि को स्थानीय समय में परिवर्तित किया जाए या समन्वित विश्व समय (UTC) के रूप में संरक्षित रखा जाए। |

### वापसी मान

[String](../../../system/string/) का [DateTime](../../../system/datetime/) समतुल्य।

## देखें

* एन्युम [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [DateTime](../../../system/datetime/)
* क्लास [String](../../../system/string/)
* क्लास [XmlConvert](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)