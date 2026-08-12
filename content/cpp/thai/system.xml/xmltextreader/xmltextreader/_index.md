---
title: XmlTextReader()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่ของคลาส XmlTextReader ด้วยสตรีมที่ระบุ
type: docs
weight: 482
url: /th/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วยสตรีมที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML เพื่ออ่าน |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วย URL และสตรีมที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ที่ใช้สำหรับแก้ไขทรัพยากรภายนอก [XmlTextReader::get_BaseURI](../get_baseuri/) จะถูกตั้งค่าเป็นค่านี้ |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML เพื่ออ่าน |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วยสตรีมและ [XmlNameTable](../../xmlnametable/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML เพื่ออ่าน |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่จะใช้ |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วย URL, สตรีมและ [XmlNameTable](../../xmlnametable/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ที่ใช้สำหรับแก้ไขทรัพยากรภายนอก [XmlTextReader::get_BaseURI](../get_baseuri/) จะถูกตั้งค่าเป็นค่านี้ หาก **url** เป็น **nullptr** **BaseURI** จะถูกตั้งค่าเป็น [String::Empty](../../../system/string/empty/) |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML เพื่ออ่าน |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่จะใช้ |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วย TextReader ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader ที่มีข้อมูล XML เพื่ออ่าน |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วย URL และ TextReader ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ที่ใช้สำหรับแก้ไขทรัพยากรภายนอก [XmlTextReader::get_BaseURI](../get_baseuri/) จะถูกตั้งค่าเป็นค่านี้ |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader ที่มีข้อมูล XML เพื่ออ่าน |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วย TextReader และ [XmlNameTable](../../xmlnametable/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader ที่มีข้อมูล XML เพื่ออ่าน |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่จะใช้ |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วย URL, TextReader และ [XmlNameTable](../../xmlnametable/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ที่ใช้สำหรับแก้ไขทรัพยากรภายนอก [XmlTextReader::get_BaseURI](../get_baseuri/) จะถูกตั้งค่าเป็นค่านี้ หาก **url** เป็น **nullptr** **BaseURI** จะถูกตั้งค่าเป็น [String::Empty](../../../system/string/empty/) |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader ที่มีข้อมูล XML เพื่ออ่าน |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่จะใช้ |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วยสตรีม, XmlNodeType และ [XmlParserContext](../../xmlparsercontext/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีส่วนของ XML เพื่อพาร์เซ |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType ของส่วน XML นี้ ซึ่งยังกำหนดว่ามีเนื้อหาอะไรได้บ้าง |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) ที่จะใช้พาร์เซ **xmlFragment** รวมถึง [XmlNameTable](../../xmlnametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, **xml:lang** ปัจจุบันและขอบเขต **xml:space** |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วยสตริง, XmlNodeType และ [XmlParserContext](../../xmlparsercontext/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | สตริงที่มีส่วนของ XML เพื่อพาร์เซ |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType ของส่วน XML นี้ ซึ่งยังกำหนดว่าสตริงส่วนนี้สามารถมีอะไรได้บ้าง |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) ที่จะใช้พาร์เซ **xmlFragment** รวมถึง [XmlNameTable](../../xmlnametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, **xml:lang** ปัจจุบันและขอบเขต **xml:space** |

## XmlTextReader::XmlTextReader(const String\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วยไฟล์ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ของไฟล์ที่มีข้อมูล XML [XmlTextReader::get_BaseURI](../get_baseuri/) จะถูกตั้งค่าเป็นค่านี้ |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) ตัวสร้าง

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlTextReader](../) ด้วยไฟล์และ [XmlNameTable](../../xmlnametable/) ที่ระบุ

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ของไฟล์ที่มีข้อมูล XML เพื่ออ่าน |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่จะใช้ |

## ดูเพิ่มเติม

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)