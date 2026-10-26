---
title: XmlTypeCode
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αντιπροσωπεύει τους τύπους σχήματος του W3C XML Schema Definition Language (XSD).
type: docs
weight: 1093
url: /el/system.xml.schema/xmltypecode/
---
## XmlTypeCode enum

Αντιπροσωπεύει τους τύπους σχήματος του W3C XML [Schema](../) Definition Language (XSD).

```cpp
enum class XmlTypeCode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 | Καμία πληροφορία τύπου. |
| Item | 1 | Ένα αντικείμενο όπως ένας κόμβος ή μια ατομική τιμή. |
| Node | 2 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| Document | 3 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| Element | 4 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| Attribute | 5 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| Namespace | 6 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| ProcessingInstruction | 7 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| Comment | 8 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| Text | 9 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| AnyAtomicType | 10 | Οποιαδήποτε ατομική τιμή μιας ένωσης. |
| UntypedAtomic | 11 | Μια αδιάτυπη ατομική τιμή. |
| String | 12 | Ένας τύπος W3C XML [Schema](../)**xs:string**. |
| Boolean | 13 | Ένας τύπος W3C XML [Schema](../)**xs:boolean**. |
| Decimal | 14 | Ένας τύπος W3C XML [Schema](../)**xs:decimal**. |
| Float | 15 | Ένας τύπος W3C XML [Schema](../)**xs:float**. |
| Double | 16 | Ένας τύπος W3C XML [Schema](../)**xs:double**. |
| Duration | 17 | Ένας τύπος W3C XML [Schema](../)**xs:Duration**. |
| DateTime | 18 | Ένας τύπος W3C XML [Schema](../)**xs:dateTime**. |
| Time | 19 | Ένας τύπος W3C XML [Schema](../)**xs:time**. |
| Date | 20 | Ένας τύπος W3C XML [Schema](../)**xs:date**. |
| GYearMonth | 21 | Ένας τύπος W3C XML [Schema](../)**xs:gYearMonth**. |
| GYear | 22 | Ένας τύπος W3C XML [Schema](../)**xs:gYear**. |
| GMonthDay | 23 | Ένας τύπος W3C XML [Schema](../)**xs:gMonthDay**. |
| GDay | 24 | Ένας τύπος W3C XML [Schema](../)**xs:gDay**. |
| GMonth | 25 | Ένας τύπος W3C XML [Schema](../)**xs:gMonth**. |
| HexBinary | 26 | Ένας τύπος W3C XML [Schema](../)**xs:hexBinary**. |
| Base64Binary | 27 | Ένας τύπος W3C XML [Schema](../)**xs:base64Binary**. |
| AnyUri | 28 | Ένας τύπος W3C XML [Schema](../)**xs:anyURI**. |
| QName | 29 | Ένας τύπος W3C XML [Schema](../)**xs:QName**. |
| Notation | 30 | Ένας τύπος W3C XML [Schema](../)**xs:NOTATION**. |
| NormalizedString | 31 | Ένας τύπος W3C XML [Schema](../)**xs:normalizedString**. |
| Token | 32 | Ένας τύπος W3C XML [Schema](../)**xs:token**. |
| Language | 33 | Ένας τύπος W3C XML [Schema](../)**xs:language**. |
| NmToken | 34 | Ένας τύπος W3C XML [Schema](../)**xs:NMTOKEN**. |
| Name | 35 | Ένας τύπος W3C XML [Schema](../)**xs:Name**. |
| NCName | 36 | Ένας τύπος W3C XML [Schema](../)**xs:NCName**. |
| Id | 37 | Ένας τύπος W3C XML [Schema](../)**xs:ID**. |
| Idref | 38 | Ένας τύπος W3C XML [Schema](../)**xs:IDREF**. |
| Entity | 39 | Ένας τύπος W3C XML [Schema](../)**xs:ENTITY**. |
| Integer | 40 | Ένας τύπος W3C XML [Schema](../)**xs:integer**. |
| NonPositiveInteger | 41 | Ένας τύπος W3C XML [Schema](../)**xs:nonPositiveInteger**. |
| NegativeInteger | 42 | Ένας τύπος W3C XML [Schema](../)**xs:negativeInteger**. |
| Long | 43 | Ένας τύπος W3C XML [Schema](../)**xs:long**. |
| Int | 44 | Ένας τύπος W3C XML [Schema](../)**xs:int**. |
| Short | 45 | Ένας τύπος W3C XML [Schema](../)**xs:short**. |
| Byte | 46 | Ένας τύπος W3C XML [Schema](../)**xs:byte**. |
| NonNegativeInteger | 47 | Ένας τύπος W3C XML [Schema](../)**xs:nonNegativeInteger**. |
| UnsignedLong | 48 | Ένας τύπος W3C XML [Schema](../)**xs:unsignedLong**. |
| UnsignedInt | 49 | Ένας τύπος W3C XML [Schema](../)**xs:unsignedInt**. |
| UnsignedShort | 50 | Ένας τύπος W3C XML [Schema](../)**xs:unsignedShort**. |
| UnsignedByte | 51 | Ένας τύπος W3C XML [Schema](../)**xs:unsignedByte**. |
| PositiveInteger | 52 | Ένας τύπος W3C XML [Schema](../)**xs:positiveInteger**. |
| YearMonthDuration | 53 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |
| DayTimeDuration | 54 | Αυτή η τιμή χρησιμοποιείται για εσωτερικούς σκοπούς και δεν προορίζεται για άμεση χρήση από τον κώδικά σας. |

## Δείτε επίσης

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)