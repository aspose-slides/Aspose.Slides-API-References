---
title: XmlTypeCode
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل أنواع مخططات لغة تعريف مخطط XML الخاص بـ W3C (XSD).
type: docs
weight: 1093
url: /ar/system.xml.schema/xmltypecode/
---
## XmlTypeCode تعداد

يمثل مخطط لغة التعريف XML الخاصة بـ W3C [Schema](../) (XSD).

```cpp
enum class XmlTypeCode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | لا توجد معلومات عن النوع. |
| Item | 1 | عنصر مثل عقدة أو قيمة ذرية. |
| Node | 2 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| Document | 3 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| Element | 4 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| Attribute | 5 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| Namespace | 6 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| ProcessingInstruction | 7 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| Comment | 8 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| Text | 9 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| AnyAtomicType | 10 | أي قيمة ذرية من اتحاد. |
| UntypedAtomic | 11 | قيمة ذرية غير مكتوبة النوع. |
| String | 12 | نوع [Schema](../)**xs:string** W3C XML. |
| Boolean | 13 | نوع [Schema](../)**xs:boolean** W3C XML. |
| Decimal | 14 | نوع [Schema](../)**xs:decimal** W3C XML. |
| Float | 15 | نوع [Schema](../)**xs:float** W3C XML. |
| Double | 16 | نوع [Schema](../)**xs:double** W3C XML. |
| Duration | 17 | نوع [Schema](../)**xs:Duration** W3C XML. |
| DateTime | 18 | نوع [Schema](../)**xs:dateTime** W3C XML. |
| Time | 19 | نوع [Schema](../)**xs:time** W3C XML. |
| Date | 20 | نوع [Schema](../)**xs:date** W3C XML. |
| GYearMonth | 21 | نوع [Schema](../)**xs:gYearMonth** W3C XML. |
| GYear | 22 | نوع [Schema](../)**xs:gYear** W3C XML. |
| GMonthDay | 23 | نوع [Schema](../)**xs:gMonthDay** W3C XML. |
| GDay | 24 | نوع [Schema](../)**xs:gDay** W3C XML. |
| GMonth | 25 | نوع [Schema](../)**xs:gMonth** W3C XML. |
| HexBinary | 26 | نوع [Schema](../)**xs:hexBinary** W3C XML. |
| Base64Binary | 27 | نوع [Schema](../)**xs:base64Binary** W3C XML. |
| AnyUri | 28 | نوع [Schema](../)**xs:anyURI** W3C XML. |
| QName | 29 | نوع [Schema](../)**xs:QName** W3C XML. |
| Notation | 30 | نوع [Schema](../)**xs:NOTATION** W3C XML. |
| NormalizedString | 31 | نوع [Schema](../)**xs:normalizedString** W3C XML. |
| Token | 32 | نوع [Schema](../)**xs:token** W3C XML. |
| Language | 33 | نوع [Schema](../)**xs:language** W3C XML. |
| NmToken | 34 | نوع [Schema](../)**xs:NMTOKEN** W3C XML. |
| Name | 35 | نوع [Schema](../)**xs:Name** W3C XML. |
| NCName | 36 | نوع [Schema](../)**xs:NCName** W3C XML. |
| Id | 37 | نوع [Schema](../)**xs:ID** W3C XML. |
| Idref | 38 | نوع [Schema](../)**xs:IDREF** W3C XML. |
| Entity | 39 | نوع [Schema](../)**xs:ENTITY** W3C XML. |
| Integer | 40 | نوع [Schema](../)**xs:integer** W3C XML. |
| NonPositiveInteger | 41 | نوع [Schema](../)**xs:nonPositiveInteger** W3C XML. |
| NegativeInteger | 42 | نوع [Schema](../)**xs:negativeInteger** W3C XML. |
| Long | 43 | نوع [Schema](../)**xs:long** W3C XML. |
| Int | 44 | نوع [Schema](../)**xs:int** W3C XML. |
| Short | 45 | نوع [Schema](../)**xs:short** W3C XML. |
| Byte | 46 | نوع [Schema](../)**xs:byte** W3C XML. |
| NonNegativeInteger | 47 | نوع [Schema](../)**xs:nonNegativeInteger** W3C XML. |
| UnsignedLong | 48 | نوع [Schema](../)**xs:unsignedLong** W3C XML. |
| UnsignedInt | 49 | نوع [Schema](../)**xs:unsignedInt** W3C XML. |
| UnsignedShort | 50 | نوع [Schema](../)**xs:unsignedShort** W3C XML. |
| UnsignedByte | 51 | نوع [Schema](../)**xs:unsignedByte** W3C XML. |
| PositiveInteger | 52 | نوع [Schema](../)**xs:positiveInteger** W3C XML. |
| YearMonthDuration | 53 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |
| DayTimeDuration | 54 | يتم استخدام هذه القيمة لأغراض داخلية ولا يُقصد استخدامها مباشرة من الشيفرة الخاصة بك. |

## انظر أيضًا

* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)