---
title: XmlTypeCode
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงประเภทสกีมของ W3C XML Schema Definition Language (XSD)。
type: docs
weight: 1093
url: /th/system.xml.schema/xmltypecode/
---
## XmlTypeCode enum

แสดงประเภทสคีมาของ W3C XML [Schema](../) Definition Language (XSD).

```cpp
enum class XmlTypeCode
```

### ค่าต่างๆ

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ไม่มีข้อมูลประเภท |
| Item | 1 | รายการหนึ่ง เช่น โหนดหรือค่าที่เป็นอะตอม |
| Node | 2 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| Document | 3 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| Element | 4 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| Attribute | 5 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| Namespace | 6 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| ProcessingInstruction | 7 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| Comment | 8 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| Text | 9 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| AnyAtomicType | 10 | ค่าที่เป็นอะตอมใดๆ ของยูเนียน |
| UntypedAtomic | 11 | ค่าที่เป็นอะตอมที่ไม่มีประเภท |
| String | 12 | ประเภท W3C XML [Schema](../)**xs:string** |
| Boolean | 13 | ประเภท W3C XML [Schema](../)**xs:boolean** |
| Decimal | 14 | ประเภท W3C XML [Schema](../)**xs:decimal** |
| Float | 15 | ประเภท W3C XML [Schema](../)**xs:float** |
| Double | 16 | ประเภท W3C XML [Schema](../)**xs:double** |
| Duration | 17 | ประเภท W3C XML [Schema](../)**xs:Duration** |
| DateTime | 18 | ประเภท W3C XML [Schema](../)**xs:dateTime** |
| Time | 19 | ประเภท W3C XML [Schema](../)**xs:time** |
| Date | 20 | ประเภท W3C XML [Schema](../)**xs:date** |
| GYearMonth | 21 | ประเภท W3C XML [Schema](../)**xs:gYearMonth** |
| GYear | 22 | ประเภท W3C XML [Schema](../)**xs:gYear** |
| GMonthDay | 23 | ประเภท W3C XML [Schema](../)**xs:gMonthDay** |
| GDay | 24 | ประเภท W3C XML [Schema](../)**xs:gDay** |
| GMonth | 25 | ประเภท W3C XML [Schema](../)**xs:gMonth** |
| HexBinary | 26 | ประเภท W3C XML [Schema](../)**xs:hexBinary** |
| Base64Binary | 27 | ประเภท W3C XML [Schema](../)**xs:base64Binary** |
| AnyUri | 28 | ประเภท W3C XML [Schema](../)**xs:anyURI** |
| QName | 29 | ประเภท W3C XML [Schema](../)**xs:QName** |
| Notation | 30 | ประเภท W3C XML [Schema](../)**xs:NOTATION** |
| NormalizedString | 31 | ประเภท W3C XML [Schema](../)**xs:normalizedString** |
| Token | 32 | ประเภท W3C XML [Schema](../)**xs:token** |
| Language | 33 | ประเภท W3C XML [Schema](../)**xs:language** |
| NmToken | 34 | ประเภท W3C XML [Schema](../)**xs:NMTOKEN** |
| Name | 35 | ประเภท W3C XML [Schema](../)**xs:Name** |
| NCName | 36 | ประเภท W3C XML [Schema](../)**xs:NCName** |
| Id | 37 | ประเภท W3C XML [Schema](../)**xs:ID** |
| Idref | 38 | ประเภท W3C XML [Schema](../)**xs:IDREF** |
| Entity | 39 | ประเภท W3C XML [Schema](../)**xs:ENTITY** |
| Integer | 40 | ประเภท W3C XML [Schema](../)**xs:integer** |
| NonPositiveInteger | 41 | ประเภท W3C XML [Schema](../)**xs:nonPositiveInteger** |
| NegativeInteger | 42 | ประเภท W3C XML [Schema](../)**xs:negativeInteger** |
| Long | 43 | ประเภท W3C XML [Schema](../)**xs:long** |
| Int | 44 | ประเภท W3C XML [Schema](../)**xs:int** |
| Short | 45 | ประเภท W3C XML [Schema](../)**xs:short** |
| Byte | 46 | ประเภท W3C XML [Schema](../)**xs:byte** |
| NonNegativeInteger | 47 | ประเภท W3C XML [Schema](../)**xs:nonNegativeInteger** |
| UnsignedLong | 48 | ประเภท W3C XML [Schema](../)**xs:unsignedLong** |
| UnsignedInt | 49 | ประเภท W3C XML [Schema](../)**xs:unsignedInt** |
| UnsignedShort | 50 | ประเภท W3C XML [Schema](../)**xs:unsignedShort** |
| UnsignedByte | 51 | ประเภท W3C XML [Schema](../)**xs:unsignedByte** |
| PositiveInteger | 52 | ประเภท W3C XML [Schema](../)**xs:positiveInteger** |
| YearMonthDuration | 53 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |
| DayTimeDuration | 54 | ค่าดังนี้ใช้สำหรับวัตถุประสงค์ภายในและไม่ได้ตั้งใจให้ใช้งานโดยตรงจากโค้ดของคุณ |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)