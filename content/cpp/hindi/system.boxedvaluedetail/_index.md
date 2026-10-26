---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: 
type: docs
weight: 287
url: /hi/system.boxedvaluedetail/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [Comparable](./comparable/) | IComparable<> का सरल कार्यान्वयन |
| [NonComparable](./noncomparable/) | IComparable<> को लागू नहीं करने वाले बॉक्स्ड प्रकारों के लिए डमी बेस टाइप |

## स्ट्रक्चर्स

| स्ट्रक्ट | विवरण |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | टेम्प्लेट प्रेडिकेट जो जाँचता है कि बॉक्स्ड ऑब्जेक्ट को स्वयं दिया गया इंटरफ़ेस लागू करना चाहिए या नहीं। |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) को लागू करता है [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | टेम्प्लेट प्रेडिकेट जो जाँचता है कि बॉक्स्ड ऑब्जेक्ट को [IComparable](../system/icomparable/) इंटरफ़ेस स्वयं लागू करना चाहिए या नहीं। |

## फ़ंक्शन्स

| फ़ंक्शन | विवरण |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | निर्दिष्ट मान की समानता को [operator==()](../system/operator_equal_equal/) का उपयोग करके निर्धारित करता है। |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | निर्दिष्ट मान की समानता को [System::Object::Equals()](../system/object/equals/) मेथड का उपयोग करके निर्धारित करता है। |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | दो सिंगल-प्रेसिशन फ़्लोटिंग-पॉइंट मानों की तुलना करता है। |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | दो डबल-प्रेसिशन फ़्लोटिंग-पॉइंट मानों की तुलना करता है। |