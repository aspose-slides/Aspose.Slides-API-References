---
title: XmlTypeCode
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: W3C XML स्कीमा परिभाषा भाषा (XSD) स्कीमा प्रकारों का प्रतिनिधित्व करता है।
type: docs
weight: 1093
url: /hi/system.xml.schema/xmltypecode/
---
## XmlTypeCode एनम

W3C XML [Schema](../) डिफिनिशन लैंग्वेज (XSD) स्कीमा प्रकारों का प्रतिनिधित्व करता है।

```cpp
enum class XmlTypeCode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | कोई प्रकार जानकारी नहीं। |
| Item | 1 | एक वस्तु जैसे नोड या परम मान। |
| Node | 2 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| Document | 3 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| Element | 4 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| Attribute | 5 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| Namespace | 6 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| ProcessingInstruction | 7 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| Comment | 8 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| Text | 9 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| AnyAtomicType | 10 | संघ का कोई भी परम मान। |
| UntypedAtomic | 11 | एक अनटाइप्ड परम मान। |
| String | 12 | एक W3C XML [Schema](../)**xs:string** प्रकार। |
| Boolean | 13 | एक W3C XML [Schema](../)**xs:boolean** प्रकार। |
| Decimal | 14 | एक W3C XML [Schema](../)**xs:decimal** प्रकार। |
| Float | 15 | एक W3C XML [Schema](../)**xs:float** प्रकार। |
| Double | 16 | एक W3C XML [Schema](../)**xs:double** प्रकार। |
| Duration | 17 | एक W3C XML [Schema](../)**xs:Duration** प्रकार। |
| DateTime | 18 | एक W3C XML [Schema](../)**xs:dateTime** प्रकार। |
| Time | 19 | एक W3C XML [Schema](../)**xs:time** प्रकार। |
| Date | 20 | एक W3C XML [Schema](../)**xs:date** प्रकार। |
| GYearMonth | 21 | एक W3C XML [Schema](../)**xs:gYearMonth** प्रकार। |
| GYear | 22 | एक W3C XML [Schema](../)**xs:gYear** प्रकार। |
| GMonthDay | 23 | एक W3C XML [Schema](../)**xs:gMonthDay** प्रकार। |
| GDay | 24 | एक W3C XML [Schema](../)**xs:gDay** प्रकार। |
| GMonth | 25 | एक W3C XML [Schema](../)**xs:gMonth** प्रकार। |
| HexBinary | 26 | एक W3C XML [Schema](../)**xs:hexBinary** प्रकार। |
| Base64Binary | 27 | एक W3C XML [Schema](../)**xs:base64Binary** प्रकार। |
| AnyUri | 28 | एक W3C XML [Schema](../)**xs:anyURI** प्रकार। |
| QName | 29 | एक W3C XML [Schema](../)**xs:QName** प्रकार। |
| Notation | 30 | एक W3C XML [Schema](../)**xs:NOTATION** प्रकार। |
| NormalizedString | 31 | एक W3C XML [Schema](../)**xs:normalizedString** प्रकार। |
| Token | 32 | एक W3C XML [Schema](../)**xs:token** प्रकार। |
| Language | 33 | एक W3C XML [Schema](../)**xs:language** प्रकार। |
| NmToken | 34 | एक W3C XML [Schema](../)**xs:NMTOKEN** प्रकार। |
| Name | 35 | एक W3C XML [Schema](../)**xs:Name** प्रकार। |
| NCName | 36 | एक W3C XML [Schema](../)**xs:NCName** प्रकार। |
| Id | 37 | एक W3C XML [Schema](../)**xs:ID** प्रकार। |
| Idref | 38 | एक W3C XML [Schema](../)**xs:IDREF** प्रकार। |
| Entity | 39 | एक W3C XML [Schema](../)**xs:ENTITY** प्रकार। |
| Integer | 40 | एक W3C XML [Schema](../)**xs:integer** प्रकार। |
| NonPositiveInteger | 41 | एक W3C XML [Schema](../)**xs:nonPositiveInteger** प्रकार। |
| NegativeInteger | 42 | एक W3C XML [Schema](../)**xs:negativeInteger** प्रकार। |
| Long | 43 | एक W3C XML [Schema](../)**xs:long** प्रकार। |
| Int | 44 | एक W3C XML [Schema](../)**xs:int** प्रकार। |
| Short | 45 | एक W3C XML [Schema](../)**xs:short** प्रकार। |
| Byte | 46 | एक W3C XML [Schema](../)**xs:byte** प्रकार। |
| NonNegativeInteger | 47 | एक W3C XML [Schema](../)**xs:nonNegativeInteger** प्रकार। |
| UnsignedLong | 48 | एक W3C XML [Schema](../)**xs:unsignedLong** प्रकार। |
| UnsignedInt | 49 | एक W3C XML [Schema](../)**xs:unsignedInt** प्रकार। |
| UnsignedShort | 50 | एक W3C XML [Schema](../)**xs:unsignedShort** प्रकार। |
| UnsignedByte | 51 | एक W3C XML [Schema](../)**xs:unsignedByte** प्रकार। |
| PositiveInteger | 52 | एक W3C XML [Schema](../)**xs:positiveInteger** प्रकार। |
| YearMonthDuration | 53 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |
| DayTimeDuration | 54 | यह मान आंतरिक प्रयोजनों के लिए उपयोग किया जाता है और इसे आपके कोड से सीधे इस्तेमाल करने के लिए नहीं है। |

## संबंधित देखें

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)