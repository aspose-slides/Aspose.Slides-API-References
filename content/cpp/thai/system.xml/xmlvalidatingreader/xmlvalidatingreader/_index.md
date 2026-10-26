---
title: XmlValidatingReader()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ใหม่ของคลาส XmlValidatingReader ที่ตรวจสอบความถูกต้องของเนื้อหาที่ส่งกลับจาก XmlReader ที่กำหนด
type: docs
weight: 430
url: /th/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

สร้างอินสแตนซ์ใหม่ของคลาส [XmlValidatingReader](../) ที่ตรวจสอบความถูกต้องของเนื้อหาที่ส่งกลับจาก [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../xmlreader/) ที่ใช้สำหรับอ่านในขณะตรวจสอบ ความสามารถของการดำเนินการในปัจจุบันสนับสนุนเฉพาะ [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

สร้างอินสแตนซ์ใหม่ของคลาส [XmlValidatingReader](../) ด้วยค่าเฉพาะที่ระบุ

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | สตริงที่มีส่วน XML ที่ต้องการแยกวิเคราะห์ |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType ของส่วน XML นี้ ซึ่งยังกำหนดว่า สตริงส่วนนี้สามารถมีอะไรได้บ้าง (ดูตารางด้านล่าง) |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) ที่ส่วน XML จะถูกแยกวิเคราะห์ ซึ่งรวมถึง [NameTable](../../nametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, **xml:lang** ปัจจุบัน, และขอบเขต **xml:space** |

## Remarks

ตารางต่อไปนี้แสดงค่าที่ถูกต้องสำหรับ **fragType** และวิธีที่ตัวอ่านประมวลผลแต่ละประเภทของโหนด

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| เนื้อหาองค์ประกอบที่ถูกต้อง (เช่น การรวมกันขององค์ประกอบ, คอมเมนต์, คำสั่งประมวลผล, cdata, ข้อความ, และอ้างอิงเอนทิตี้) |
| [Attribute](../../../system/attribute/)| ค่าของแอทริบิวต์ (ส่วนที่อยู่ในเครื่องหมายอัญประกาศ) |
| Document| เนื้อหาของเอกสาร XML ทั้งหมด; ซึ่งบังคับใช้กฎระดับเอกสาร |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

สร้างอินสแตนซ์ใหม่ของคลาส [XmlValidatingReader](../) ด้วยค่าเฉพาะที่ระบุ

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีส่วน XML ที่ต้องการแยกวิเคราะห์ |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType ของส่วน XML นี้ ซึ่งกำหนดว่า ส่วนนี้สามารถมีอะไรได้บ้าง (ดูตารางด้านล่าง) |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) ที่ส่วน XML จะถูกแยกวิเคราะห์ ซึ่งรวมถึง [XmlNameTable](../../xmlnametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, **xml:lang** ปัจจุบัน, และขอบเขต **xml:space** |

## Remarks

ตารางต่อไปนี้แสดงค่าที่ถูกต้องสำหรับ **fragType** และวิธีที่ตัวอ่านประมวลผลแต่ละประเภทของโหนด

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| เนื้อหาองค์ประกอบที่ถูกต้อง (เช่น การรวมกันขององค์ประกอบ, คอมเมนต์, คำสั่งประมวลผล, cdata, ข้อความ, และอ้างอิงเอนทิตี้) |
| [Attribute](../../../system/attribute/)| ค่าของแอทริบิวต์ (ส่วนที่อยู่ในเครื่องหมายอัญประกาศ) |
| Document| เนื้อหาของเอกสาร XML ทั้งหมด; ซึ่งบังคับใช้กฎระดับเอกสาร |

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)