---
title: Create()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ XmlReader ใหม่พร้อม URI ที่ระบุ.
type: docs
weight: 1015
url: /th/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่พร้อม URI ที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของไฟล์ที่มีข้อมูล XML. คลาส [XmlUrlResolver](../../xmlurlresolver/) ใช้สำหรับแปลงเส้นทางเป็นรูปแบบข้อมูลมาตรฐาน. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ URI และการตั้งค่าที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของไฟล์ที่มีข้อมูล XML. วัตถุ [XmlResolver](../../xmlresolver/) บนวัตถุ [XmlReaderSettings](../../xmlreadersettings/) ใช้เพื่อแปลงเส้นทางเป็นรูปแบบข้อมูลมาตรฐาน หากค่าของ XmlReaderSettings::get_XmlResolver เป็น **nullptr** จะใช้วัตถุ [XmlUrlResolver](../../xmlurlresolver/) ใหม่. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ URI, การตั้งค่า และข้อมูลบริบทสำหรับการพาร์เซ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของไฟล์ที่มีข้อมูล XML. วัตถุ [XmlResolver](../../xmlresolver/) บนวัตถุ [XmlReaderSettings](../../xmlreadersettings/) ใช้เพื่อแปลงเส้นทางเป็นรูปแบบข้อมูลมาตรฐาน หากค่าของ XmlReaderSettings::get_XmlResolver เป็น **nullptr** จะใช้วัตถุ [XmlUrlResolver](../../xmlurlresolver/) ใหม่. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | ข้อมูลบริบทที่จำเป็นสำหรับการพาร์เซส่วนย่อยของ XML. ข้อมูลบริบทอาจรวมถึง [XmlNameTable](../../xmlnametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, ขอบเขต **xml:lang** และ **xml:space** ปัจจุบัน, URI ฐาน, และการกำหนดประเภทเอกสาร. ค่านี้อาจเป็น **nullptr**. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้สตรีมที่ระบุพร้อมการตั้งค่าเริ่มต้น

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML. [XmlReader](../) จะสแกนไบต์แรกของสตรีมเพื่อค้นหาเครื่องหมายลำดับไบต์หรือสัญญาณอื่นของการเข้ารหัส. เมื่อกำหนดการเข้ารหัสแล้ว การเข้ารหัสจะถูกใช้ต่อเพื่ออ่านสตรีม, และการประมวลผลจะดำเนินต่อด้วยการพาร์เซอินพุตเป็นสตรีมของอักขระ (Unicode). |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่ด้วยสตรีมและการตั้งค่าที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML. [XmlReader](../) จะสแกนไบต์แรกของสตรีมเพื่อค้นหาเครื่องหมายลำดับไบต์หรือสัญญาณอื่นของการเข้ารหัส. เมื่อกำหนดการเข้ารหัสแล้ว การเข้ารหัสจะถูกใช้ต่อเพื่ออ่านสตรีม, และการประมวลผลจะดำเนินต่อด้วยการพาร์เซอินพุตเป็นสตรีมของอักขระ (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้สตรีม, URI ฐาน, และการตั้งค่าที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML. [XmlReader](../) จะสแกนไบต์แรกของสตรีมเพื่อค้นหาเครื่องหมายลำดับไบต์หรือสัญญาณอื่นของการเข้ารหัส. เมื่อกำหนดการเข้ารหัสแล้ว การเข้ารหัสจะถูกใช้ต่อเพื่ออ่านสตรีม, และการประมวลผลจะดำเนินต่อด้วยการพาร์เซอินพุตเป็นสตรีมของอักขระ (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | URI ฐานสำหรับเอนทิตี้หรือเอกสารที่กำลังอ่าน ค่านี้อาจเป็น **nullptr**. **[Security](../../../system.security/) Note** URI ฐานใช้ในการแก้ไข URI ที่สัมพันธ์ของเอกสาร XML. อย่าใช้ URI ฐานจากแหล่งที่ไม่ไว้ใจ. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้สตรีม, การตั้งค่า, และข้อมูลบริบทสำหรับการพาร์เซ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูล XML. [XmlReader](../) จะสแกนไบต์แรกของสตรีมเพื่อค้นหาเครื่องหมายลำดับไบต์หรือสัญญาณอื่นของการเข้ารหัส. เมื่อกำหนดการเข้ารหัสแล้ว การเข้ารหัสจะถูกใช้ต่อเพื่ออ่านสตรีม, และการประมวลผลจะดำเนินต่อด้วยการพาร์เซอินพุตเป็นสตรีมของอักขระ (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | ข้อมูลบริบทที่จำเป็นสำหรับการพาร์เซส่วนย่อยของ XML. ข้อมูลบริบทอาจรวมถึง [XmlNameTable](../../xmlnametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, ขอบเขต **xml:lang** และ **xml:space** ปัจจุบัน, URI ฐาน, และการกำหนดประเภทเอกสาร. ค่านี้อาจเป็น **nullptr**. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ตัวอ่านข้อความที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | ตัวอ่านข้อความที่ใช้เพื่ออ่านข้อมูล XML. ตัวอ่านข้อความจะส่งคืนสตรีมของอักขระ Unicode ดังนั้นการเข้ารหัสที่ระบุในประกาศ XML จะไม่ถูกใช้โดย XML reader เพื่อถอดรหัสสตรีมข้อมูล. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ตัวอ่านข้อความและการตั้งค่าที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | ตัวอ่านข้อความที่ใช้เพื่ออ่านข้อมูล XML. ตัวอ่านข้อความจะส่งคืนสตรีมของอักขระ Unicode ดังนั้นการเข้ารหัสที่ระบุในประกาศ XML จะไม่ถูกใช้โดย XML reader เพื่อถอดรหัสสตรีมข้อมูล. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | การตั้งค่าสำหรับ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ตัวอ่านข้อความ, การตั้งค่า, และ URI ฐานที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | ตัวอ่านข้อความที่ใช้เพื่ออ่านข้อมูล XML. ตัวอ่านข้อความจะส่งคืนสตรีมของอักขระ Unicode ดังนั้นการเข้ารหัสที่ระบุในประกาศ XML จะไม่ถูกใช้โดย [XmlReader](../) เพื่อถอดรหัสสตรีมข้อมูล. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | URI ฐานสำหรับเอนทิตี้หรือเอกสารที่กำลังอ่าน ค่านี้อาจเป็น **nullptr**. **[Security](../../../system.security/) Note** URI ฐานใช้ในการแก้ไข URI ที่สัมพันธ์ของเอกสาร XML. อย่าใช้ URI ฐานจากแหล่งที่ไม่ไว้ใจ. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ตัวอ่านข้อความ, การตั้งค่า, และข้อมูลบริบทสำหรับการพาร์เซ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | ตัวอ่านข้อความที่ใช้เพื่ออ่านข้อมูล XML. ตัวอ่านข้อความจะส่งคืนสตรีมของอักขระ Unicode ดังนั้นการเข้ารหัสที่ระบุในประกาศ XML จะไม่ถูกใช้โดย XML reader เพื่อถอดรหัสสตรีมข้อมูล. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ค่านี้อาจเป็น **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | ข้อมูลบริบทที่จำเป็นสำหรับการพาร์เซส่วนย่อยของ XML. ข้อมูลบริบทอาจรวมถึง [XmlNameTable](../../xmlnametable/) ที่ใช้, การเข้ารหัส, ขอบเขตเนมสเปซ, ขอบเขต **xml:lang** และ **xml:space** ปัจจุบัน, URI ฐาน, และการกำหนดประเภทเอกสาร. ค่านี้อาจเป็น **nullptr**. |

### Return Value

ออปเจ็กต์ที่ใช้เพื่ออ่านข้อมูล XML ในสตรีม.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method

สร้างอินสแตนซ์ [XmlReader](../) ใหม่โดยใช้ XML reader และการตั้งค่าที่ระบุ

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | วัตถุที่คุณต้องการใช้เป็น XML reader พื้นฐาน. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | การตั้งค่าสำหรับอินสแตนซ์ [XmlReader](../) ใหม่ ระดับความสอดคล้องของวัตถุ [XmlReaderSettings](../../xmlreadersettings/) จะต้องตรงกับระดับความสอดคล้องของ reader พื้นฐาน หรือจะต้องตั้งเป็น [ConformanceLevel::Auto](../../conformancelevel/). |

### Return Value

ออปเจ็กต์ที่ห่มรอบวัตถุ [XmlReader](../) ที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlReader](../)
* คลาส [String](../../../system/string/)
* คลาส [XmlReaderSettings](../../xmlreadersettings/)
* คลาส [XmlParserContext](../../xmlparsercontext/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [TextReader](../../../system.io/textreader/)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)