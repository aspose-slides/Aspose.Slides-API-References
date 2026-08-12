---
title: XmlTextWriter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ของคลาส XmlTextWriter โดยใช้สตรีมและการเข้ารหัสที่ระบุ
type: docs
weight: 183
url: /th/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) คอนสตรัคเตอร์


สร้างอินสแตนซ์ของคลาส [XmlTextWriter](../) ด้วยสตรีมและการเข้ารหัสที่ระบุ

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่คุณต้องการเขียน |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ต้องการสร้าง หากการเข้ารหัสเป็น **nullptr** จะเขียนสตรีมเป็น UTF-8 และละเว้นแอตทริบิวต์ encoding จาก **ProcessingInstruction** |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) คอนสตรัคเตอร์


สร้างอินสแตนซ์ของคลาส [XmlTextWriter](../) ด้วยไฟล์ที่ระบุ

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ชื่อไฟล์ที่ต้องการเขียน หากไฟล์มีอยู่แล้วจะทำการตัดและเขียนทับด้วยเนื้อหาใหม่ |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ต้องการสร้าง หากการเข้ารหัสเป็น **nullptr** จะเขียนไฟล์เป็น UTF-8 และละเว้นแอตทริบิวต์ encoding จาก **ProcessingInstruction** |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) คอนสตรัคเตอร์


สร้างอินสแตนซ์ของคลาส [XmlTextWriter](../) ด้วย TextWriter ที่ระบุ

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่จะเขียนไป ถือว่ามีการตั้งค่า encoding ที่ถูกต้องแล้ว |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [Encoding](../../../system.text/encoding/)
* คลาส [XmlTextWriter](../)
* คลาส [String](../../../system/string/)
* คลาส [TextWriter](../../../system.io/textwriter/)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)