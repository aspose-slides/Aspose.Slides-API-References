---
title: BinaryReader()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างอินสแตนซ์ของคลาส BinaryReader ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัส UTF-8
type: docs
weight: 1
url: /th/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor

สร้างอินสแตนซ์ของคลาส [BinaryReader](../) ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัส UTF-8

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมอินพุต |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

สร้างอินสแตนซ์ของคลาส [BinaryReader](../) ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมอินพุต |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ใช้ |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor

สร้างอินสแตนซ์ของคลาส [BinaryReader](../) ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมอินพุต |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ใช้ |
| leaveOpen | **bool** | ระบุว่าควรปล่อยสตรีม **input** ให้อยู่เปิด (true) หลังจากวัตถุปัจจุบันถูกทำลายหรือไม่ (false) |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../stream/)
* คลาส [BinaryReader](../)
* คลาส [Encoding](../../../system.text/encoding/)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)