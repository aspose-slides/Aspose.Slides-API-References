---
title: ToSingle()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจุดลอยความแม่นยำเดี่ยว
type: docs
weight: 131
url: /th/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) method

แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจุดลอยความแม่นยำเดี่ยว

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่ประกอบด้วยไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ต้องเริ่มรับไบต์เพื่อแปลง |

### ค่าที่ส่งคืน

ค่าจุดลอยความแม่นยำเดี่ยวที่ได้จากการแปลง

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) method

แปลงสี่ไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าจุดลอยความแม่นยำเดี่ยว

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่ประกอบด้วยไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่ต้องเริ่มรับไบต์เพื่อแปลง |

### ค่าที่ส่งคืน

ค่าจุดลอยความแม่นยำเดี่ยวที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)