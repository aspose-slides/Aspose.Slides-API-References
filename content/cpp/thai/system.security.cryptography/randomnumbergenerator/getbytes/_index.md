---
title: GetBytes()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เติมองค์ประกอบของอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.
type: docs
weight: 14
url: /th/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) เมธอด

เติมองค์ประกอบของอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ต้องการเติม. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) เมธอด

เติมส่วนของอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ไบต์ที่ต้องการเติมส่วน. |
| offset | int | ดัชนีเริ่มต้นของส่วน. |
| count | int | ขนาดของส่วน. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) เมธอด

เติมองค์ประกอบของวิวอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | วิวอาเรย์ไบต์ที่ต้องการเติม. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) เมธอด

เติมส่วนของวิวอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | วิวอาเรย์ไบต์ที่ต้องการเติมส่วน. |
| offset | int | ดัชนีเริ่มต้นของส่วน. |
| count | int | ขนาดของส่วน. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) เมธอด

เติมองค์ประกอบของสแตกอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | สแตกอาเรย์ไบต์ที่ต้องการเติม. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) เมธอด

เติมส่วนของสแตกอาเรย์ที่มีอยู่ด้วยไบต์แบบสุ่ม.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | สแตกอาเรย์ไบต์ที่ต้องการเติมส่วน. |
| offset | int | ดัชนีเริ่มต้นของส่วน. |
| count | int | ขนาดของส่วน. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [RandomNumberGenerator](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)