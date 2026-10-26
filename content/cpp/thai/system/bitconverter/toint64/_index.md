---
title: ToInt64()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แปลงไบต์แปดไบต์จากอาร์เรย์ที่ระบุเริ่มที่ตำแหน่งที่ระบุเป็นค่าจำนวนเต็ม 64-บิต
type: docs
weight: 79
url: /th/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) เมธอด

แปลงไบต์แปดไบต์จากอาร์เรย์ที่ระบุเริ่มที่ตำแหน่งที่ระบุเป็นค่าจำนวนเต็มแบบ 64-บิต

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่เริ่มดึงไบต์เพื่อแปลง |

### ค่าที่คืน

ค่าจำนวนเต็มแบบ 64-บิตที่ได้จากการแปลง

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) เมธอด

แปลงไบต์แปดไบต์จากอาร์เรย์ที่ระบุเริ่มที่ตำแหน่งที่ระบุเป็นค่าจำนวนเต็มแบบ 64-บิต

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์สำหรับการแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่เริ่มดึงไบต์เพื่อแปลง |

### ค่าที่คืน

ค่าจำนวนเต็มแบบ 64-บิตที่ได้จากการแปลง

## ดูเพิ่มเติม

* การกำหนดประเภท [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)