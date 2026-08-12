---
title: ToUInt64()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุให้เป็นค่าจำนวนเต็มบวก 64-บิตแบบไม่มีเครื่องหมายบวก
type: docs
weight: 118
url: /th/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) method

แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุให้เป็นค่าจำนวนเต็มบวก 64-บิตแบบไม่มีเครื่องหมายบวก

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ใช้เริ่มต้นการรับไบต์เพื่อแปลง |

### ค่าที่ส่งกลับ

ค่าจำนวนเต็มบวก 64-บิตที่ได้จากการแปลง

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) method

แปลงแปดไบต์จากอาร์เรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุให้เป็นค่าจำนวนเต็มบวก 64-บิตแบบไม่มีเครื่องหมายบวก

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ใช้เริ่มต้นการรับไบต์เพื่อแปลง |

### ค่าที่ส่งกลับ

ค่าจำนวนเต็มบวก 64-บิตที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)