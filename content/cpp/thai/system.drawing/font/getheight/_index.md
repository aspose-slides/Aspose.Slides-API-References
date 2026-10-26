---
title: GetHeight()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนระยะห่างบรรทัดของแบบอักษรที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน, ในหน่วยปัจจุบันของอ็อบเจ็กต์ Graphics ที่ระบุ
type: docs
weight: 14
url: /th/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) เมธอด

ส่งคืนระยะห่างบรรทัดของแบบอักษรที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน, ในหน่วยปัจจุบันของวัตถุ [Graphics](../../graphics/) ที่ระบุ

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | อ็อบเจ็กต์ [Graphics](../../graphics/) ที่ระบุหน่วยการวัด |

## Font::GetHeight(float) เมธอด

ส่งคืนความสูงของแบบอักษรที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันเมื่อวาดบนอุปกรณ์แสดงผลด้วยความละเอียดแนวตั้งที่ระบุ

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dpi | **float** | ความละเอียดแนวตั้งของอุปกรณ์แสดงผล |

### ค่าที่ส่งกลับ

ความสูงของแบบอักษรในหน่วยพิกเซล

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Graphics](../../graphics/)
* คลาส [Font](../)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)