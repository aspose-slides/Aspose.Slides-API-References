---
title: ToUInt16()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าเต็มจำนวนเต็มไม่เซ็นต์ขนาด 16 บิต
type: docs
weight: 92
url: /th/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) เมธอด

แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าเต็มจำนวนเต็มไม่ลงนามขนาด 16 บิต

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) ที่มีไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่เริ่มการดึงไบต์เพื่อแปลง |

### ค่าที่ส่งคืน

ค่าเลขจำนวนเต็มแบบไม่เซ็นต์ขนาด 16 บิตที่ได้จากการแปลง

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) เมธอด

แปลงสองไบต์จากอาร์เรย์ที่ระบุโดยเริ่มที่ดัชนีที่ระบุเป็นค่าเต็มจำนวนเต็มไม่ลงนามขนาด 16 บิต

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView ที่มีไบต์เพื่อแปลง |
| startIndex | int | [Index](../../index/) ในอาร์เรย์ที่เริ่มการดึงไบต์เพื่อแปลง |

### ค่าที่ส่งคืน

ค่าเลขจำนวนเต็มแบบไม่เซ็นต์ขนาด 16 บิตที่ได้จากการแปลง

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [BitConverter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)