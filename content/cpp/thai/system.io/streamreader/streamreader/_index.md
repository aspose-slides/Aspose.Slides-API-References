---
title: StreamReader()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ของอ็อบเจ็กต์ StreamReader ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ที่มีขนาดเริ่มต้น 1024 ไบต์.
type: docs
weight: 1
url: /th/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ที่มีขนาดเริ่มต้น 1024 ไบต์.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมฐานที่ใช้ในการอ่านอักขระ |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ที่มีขนาดเริ่มต้น 1024 ไบต์. พารามิเตอร์ระบุว่าควรเปิดการตรวจจับเครื่องหมายลำดับไบต์หรือไม่.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมฐานที่ใช้ในการอ่านอักขระ |
| detectEncodingFromByteOrderMarks | **bool** | true เพื่อค้นหาเครื่องหมายลำดับไบต์ที่จุดเริ่มต้นของสตรีม, มิฉะนั้น false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ที่มีขนาดเริ่มต้น 1024 ไบต์.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมฐานที่ใช้ในการอ่านอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ที่มีขนาดเริ่มต้น 1024 ไบต์. พารามิเตอร์ระบุว่าควรเปิดการตรวจจับเครื่องหมายลำดับไบต์หรือไม่.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมฐานที่ใช้ในการอ่านอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| detectEncodingFromByteOrderMarks | **bool** | true เพื่อค้นหาเครื่องหมายลำดับไบต์ที่จุดเริ่มต้นของสตรีม, มิฉะนั้น false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ที่มีขนาดตามที่กำหนด. พารามิเตอร์ระบุว่าควรเปิดการตรวจจับเครื่องหมายลำดับไบต์หรือไม่.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | สตรีมฐานที่ใช้ในการอ่านอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| detectEncodingFromByteOrderMarks | **bool** | true เพื่อค้นหาเครื่องหมายลำดับไบต์ที่จุดเริ่มต้นของสตรีม, มิฉะนั้น false |
| bufferSize | int | ขนาดขั้นต่ำของบัฟเฟอร์เป็นไบต์ |

## StreamReader::StreamReader(const System::String\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ที่มีขนาดเริ่มต้น 4096 ไบต์.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | พาธของไฟล์ที่ใช้ในการอ่านอักขระ |

## StreamReader::StreamReader(const System::String\&, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ที่มีขนาดเริ่มต้น 4096 ไบต์. พารามิเตอร์ระบุว่าควรเปิดการตรวจจับเครื่องหมายลำดับไบต์หรือไม่.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | พาธของไฟล์ที่ใช้ในการอ่านอักขระ |
| detectEncodingFromByteOrderMarks | **bool** | true เพื่อค้นหาเครื่องหมายลำดับไบต์ที่จุดเริ่มต้นของไฟล์, มิฉะนั้น false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ที่มีขนาดเริ่มต้น 4096 ไบต์.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | พาธของไฟล์ที่ใช้ในการอ่านอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากสตรีมฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ที่มีขนาดเริ่มต้น 4096 ไบต์. พารามิเตอร์ระบุว่าควรเปิดการตรวจจับเครื่องหมายลำดับไบต์หรือไม่.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | พาธของไฟล์ที่ใช้ในการอ่านอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| detectEncodingFromByteOrderMarks | **bool** | true เพื่อค้นหาเครื่องหมายลำดับไบต์ที่จุดเริ่มต้นของไฟล์, มิฉะนั้น false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของวัตถุ [StreamReader](../) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ที่มีขนาดตามที่กำหนด. พารามิเตอร์ระบุว่าควรเปิดการตรวจจับเครื่องหมายลำดับไบต์หรือไม่.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | พาธของไฟล์ที่ใช้ในการอ่านอักขระ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| detectEncodingFromByteOrderMarks | **bool** | true เพื่อค้นหาเครื่องหมายลำดับไบต์ที่จุดเริ่มต้นของไฟล์, มิฉะนั้น false |
| bufferSize | int | ขนาดขั้นต่ำของบัฟเฟอร์เป็นไบต์ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)