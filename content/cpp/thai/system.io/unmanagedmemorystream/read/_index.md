---
title: Read()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ
type: docs
weight: 144
url: /th/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่านมา |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่ 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่อ่านได้

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | วิวของอาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่านมา |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่ 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่อ่านได้

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [UnmanagedMemoryStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)