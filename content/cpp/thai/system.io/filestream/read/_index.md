---
title: Read()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ
type: docs
weight: 183
url: /th/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่อิงจากศูนย์ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่านได้

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาร์เรย์ไบต์สำหรับเขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่อิงจากศูนย์ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่านได้

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [FileStream](../)
* เนมส페ซ [System::IO](../../)
* Library [Aspose.Slides](../../../)