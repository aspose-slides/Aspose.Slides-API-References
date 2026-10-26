---
title: Write()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม.
type: docs
weight: 248
url: /th/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ที่ประกอบด้วยไบต์ที่จะเขียน. |
| offset | **int32_t** | ดัชนีเริ่มจาก 0 ของ **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น. |
| count | **int32_t** | จำนวนของสมาชิกในช่วงย่อยที่จะเขียน. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด


เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | อาร์เรย์วิวที่ประกอบด้วยไบต์ที่จะเขียน. |
| offset | **int32_t** | ดัชนีเริ่มจาก 0 ของ **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น. |
| count | **int32_t** | จำนวนของสมาชิกในช่วงย่อยที่จะเขียน. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [FileStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)