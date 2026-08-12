---
title: Read()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ
type: docs
weight: 196
url: /th/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ไบต์ที่บิตที่อ่านจะถูกเขียนลง |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่อ่าน

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาร์เรย์ไบต์ที่บิตที่อ่านจะเขียนลงไป |
| offset | **int32_t** | ตำแหน่งเริ่มต้นจาก 0 ใน **buffer** เพื่อเริ่มเขียน |
| size | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่อ่าน

## ดูเพิ่มเติม

* ประเภทกำหนด [ArrayPtr](../../../system/arrayptr/)
* คลาส [NetworkStream](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)