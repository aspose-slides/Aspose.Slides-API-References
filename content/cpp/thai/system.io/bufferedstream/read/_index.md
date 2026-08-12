---
title: Read()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อ่านจำนวนไบต์ที่ระบุจากสตรีมพื้นฐานและเขียนลงในอาร์เรย์ไบต์ที่ระบุ
type: docs
weight: 53
url: /th/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมพื้นฐานและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่ใช้เขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่เริ่มจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งคืน

จำนวนไบต์ที่อ่าน

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด


อ่านจำนวนไบต์ที่ระบุจากสตรีมพื้นฐานและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่ใช้เขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่เริ่มจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งคืน

จำนวนไบต์ที่อ่าน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [BufferedStream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)