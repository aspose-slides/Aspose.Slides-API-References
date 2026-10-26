---
title: StreamWriter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ของอ็อบเจกต์ StreamWriter ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์.
type: docs
weight: 1
url: /th/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamWriter](../) ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมพื้นฐานที่ใช้เขียนอักขระ |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamWriter](../) ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่กำหนดและบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมพื้นฐานที่ใช้เขียนอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamWriter](../) ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่กำหนดและบัฟเฟอร์ขนาดตามที่ระบุ พารามิเตอร์ระบุว่าควรปิดสตรีมพื้นฐานหรือไม่เมื่ออ็อบเจกต์ [StreamWriter](../) ถูกทำลาย.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมพื้นฐานที่ใช้เขียนอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| buffer_size | int | ขนาดขั้นต่ำของบัฟเฟอร์เป็นไบต์ |
| leave_open | **bool** | ระบุว่าควรปล่อยให้สตรีมพื้นฐานเปิดอยู่หลังจากอ็อบเจกต์ [StreamWriter](../) ปัจจุบันถูกทำลายหรือไม่ |

## StreamWriter::StreamWriter(const String\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamWriter](../) ที่เขียนอักขระไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | พาธของไฟล์ที่ใช้เขียนอักขระ |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamWriter](../) ที่เขียนอักขระไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่กำหนดและบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ พารามิเตอร์ระบุว่าข้อมูลควรต่อท้ายไฟล์ที่ระบุ (true) หรือไฟล์ควรถูกเขียนทับ (false).

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | พาธของไฟล์ที่ใช้เขียนอักขระ |
| append | **bool** | ระบุว่าข้อมูลควรต่อท้ายไฟล์ที่ระบุ (true) หรือไฟล์ควรถูกเขียนทับ (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamWriter](../) ที่เขียนอักขระไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่กำหนดและขนาดบัฟเฟอร์ พารามิเตอร์ระบุว่าข้อมูลควรต่อท้ายไฟล์หรือไฟล์ควรถูกเขียนทับ.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | พาธของไฟล์ที่ใช้เขียนอักขระ |
| append | **bool** | ระบุว่าข้อมูลควรต่อท้ายไฟล์ที่ระบุ (true) หรือไฟล์ควรถูกเขียนทับ (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| buffer_size | int | ขนาดบัฟเฟอร์ที่ใช้ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)