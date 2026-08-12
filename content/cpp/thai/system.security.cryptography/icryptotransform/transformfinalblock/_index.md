---
title: TransformFinalBlock()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ประมวลผลบล็อกข้อมูลสุดท้ายและคำนวณค่าผลลัพธ์.
type: docs
weight: 14
url: /th/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) เมธอด

ประมวลผลบล็อกข้อมูลสุดท้ายและคำนวณค่าผลลัพธ์

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลจาก |
| inputOffset | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| inputCount | int | จำนวนไบต์ที่ต้องประมวลผล |

### ค่าที่ส่งคืน

ผลลัพธ์ที่คำนวณสำหรับลำดับอินพุตทั้งหมด

## ดูเพิ่มเติม

* ชนิดกำหนด [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)