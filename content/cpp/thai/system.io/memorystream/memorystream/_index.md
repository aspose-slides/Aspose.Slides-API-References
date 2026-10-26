---
title: MemoryStream()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของคลาส MemoryStream ที่มีความจุเริ่มต้นเท่ากับ 0.
type: docs
weight: 1
url: /th/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [MemoryStream](../) โดยมีความจุเริ่มต้นเท่ากับ 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [MemoryStream](../) ที่แสดงถึงสตรีมที่อิงตามบัฟเฟอร์หน่วยความจำขนาดที่ระบุ.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| capacity_ | int | ขนาดเป็นไบต์ของบัฟเฟอร์หน่วยความจำที่เชื่อมโยงกับสตรีมที่อ้างอิงโดยอ็อบเจ็กต์ที่กำลังสร้าง |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [MemoryStream](../) ที่แสดงถึงสตรีมหน่วยความจำที่เชื่อมต่อกับบัฟเฟอร์หน่วยความจำที่กำหนด พารามิเตอร์ระบุว่าสตรีมสามารถเขียนได้หรือไม่.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ของไบต์ที่จะใช้เป็นบัฟเฟอร์หน่วยความจำที่สตรีมที่อ้างอิงโดยอ็อบเจ็กต์ที่กำลังสร้างจะอิงอยู่ |
| writable | **bool** | ระบุว่าสตรีมควรจะสามารถเขียนได้หรือไม่ |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [MemoryStream](../) ที่แสดงถึงสตรีมหน่วยความจำที่เชื่อมต่อกับเซกเมนต์ของบัฟเฟอร์หน่วยความจำที่ระบุ เริ่มจากดัชนีที่ระบุและรวมจำนวนองค์ประกอบตามที่กำหนด พารามิเตอร์ระบุว่าสตรีมควรจะสามารถเขียนได้และว่าเมธอด GetBytes() สามารถเรียกใช้ได้หรือไม่.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ของไบต์ที่ส่วนหนึ่งของมันจะใช้เป็นบัฟเฟอร์หน่วยความจำที่สตรีมที่อ้างอิงโดยอ็อบเจ็กต์ที่กำลังสร้างจะอิงอยู่ |
| index | int | ดัชนีเริ่มต้นที่ 0 ของอิลีเมนต์ใน **content** ที่เซกเมนต์เริ่มต้น |
| count | int | จำนวนองค์ประกอบของ **content** ที่รวมอยู่ในเซกเมนต์ |
| writable | **bool** | ระบุว่าสตรีมควรจะสามารถเขียนได้หรือไม่ |
| publiclyVisible | **bool** | ระบุว่าบัฟเฟอร์หน่วยความจำพื้นฐานควรทำให้ผู้เรียกเมธอด GetByte() เข้าถึงได้หรือไม่ |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [MemoryStream](../)
* เนมส페ซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)