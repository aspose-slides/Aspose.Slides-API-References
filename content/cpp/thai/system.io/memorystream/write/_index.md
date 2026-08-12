---
title: Write()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม
type: docs
weight: 92
url: /th/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มจากศูนย์ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาเรย์ที่บรรจุไบต์ที่จะเขียน |
| offset | **int32_t** | ดัชนีเริ่มจากศูนย์ขององค์ประกอบใน **buffer** ที่ช่วงย่อยที่จะเขียนเริ่มต้น |
| count | **int32_t** | จำนวนขององค์ประกอบในช่วงย่อยที่จะเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [MemoryStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)