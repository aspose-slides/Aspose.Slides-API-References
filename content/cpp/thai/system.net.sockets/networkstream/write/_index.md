---
title: Write()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม.
type: docs
weight: 209
url: /th/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่มีไบต์สำหรับการเขียน |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด


เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองของอาเรย์ที่มีไบต์สำหรับการเขียน |
| offset | **int32_t** | ดัชนีเริ่มจาก 0 ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| size | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [NetworkStream](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)