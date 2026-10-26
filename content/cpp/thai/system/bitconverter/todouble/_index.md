---
title: ToDouble()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงไบต์จำนวนแปดจากอาร์เรย์ที่ระบุโดยเริ่มจากตำแหน่งที่กำหนดเป็นค่าตัวเลขจุดลอยแบบ double-precision
type: docs
weight: 144
url: /th/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method

แปลงไบต์จำนวนแปดจากอาร์เรย์ที่ระบุโดยเริ่มจากตำแหน่งที่กำหนดเป็นค่าจำนวนจริงแบบ double-precision

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ใช้เริ่มต้นการดึงไบต์เพื่อแปลง |

### ค่าที่ส่งคืน

ค่าจำนวนจริงแบบ double-precision ที่ได้จากการแปลง

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method

แปลงไบต์จำนวนแปดจากอาร์เรย์ที่ระบุโดยเริ่มจากตำแหน่งที่กำหนดเป็นค่าจำนวนจริงแบบ double-precision

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ใช้เริ่มต้นการดึงไบต์เพื่อแปลง |

### ค่าที่ส่งคืน

ค่าจำนวนจริงแบบ double-precision ที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)