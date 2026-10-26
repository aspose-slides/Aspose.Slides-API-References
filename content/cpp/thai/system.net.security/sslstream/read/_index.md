---
title: Read()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ
type: docs
weight: 391
url: /th/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาเรย์ไบต์ที่ใช้เขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่อิงศูนย์ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่านได้

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | อาเรย์ไบต์ที่ใช้เขียนไบต์ที่อ่านได้ |
| offset | **int32_t** | ตำแหน่งเริ่มต้นที่อิงศูนย์ใน **buffer** เพื่อเริ่มเขียน |
| count | **int32_t** | จำนวนไบต์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่านได้

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [SslStream](../)
* เนมสเปซ [System::Net::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)