---
title: ComputeHash()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ทำแฮชบัฟเฟอร์.
type: docs
weight: 14
url: /th/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) เมธอด


ทำแฮชบัฟเฟอร์.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | บัฟเฟอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ค่าแฮชที่คำนวณได้.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) เมธอด


ทำแฮชส่วนของบัฟเฟอร์.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | บัฟเฟอร์ต้นทาง. |
| offset | int | ตำแหน่งเริ่มต้นในบัฟเฟอร์ต้นทาง. |
| count | int | จำนวนไบต์ที่ใช้จากบัฟเฟอร์ต้นทาง. |

### ค่าที่ส่งกลับ

ค่าแฮชที่คำนวณได้.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) เมธอด


อ่านสตรีมจนถึงจุดสิ้นสุดและคำนวณแฮชสำหรับข้อมูลที่อ่าน.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | สตรีมเพื่ออ่านข้อมูลจาก. |

### ค่าที่ส่งกลับ

ค่าแฮชที่คำนวณได้สำหรับข้อมูลสตรีมทั้งหมด.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [HashAlgorithm](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมส페ซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)