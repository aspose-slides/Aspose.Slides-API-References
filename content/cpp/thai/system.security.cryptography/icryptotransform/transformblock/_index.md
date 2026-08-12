---
title: TransformBlock()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประมวลผลบล็อกข้อมูลและคัดลอกข้อมูลไปยังอาเรย์ผลลัพธ์.
type: docs
weight: 1
url: /th/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

ประมวลผลบล็อกข้อมูลและคัดลอกข้อมูลไปยังอาเรย์ผลลัพธ์.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลจาก |
| inputOffset | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| inputCount | int | จำนวนไบต์ที่ต้องประมวลผล |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ผลลัพธ์เพื่อคัดลอกข้อมูลเข้า; nullptr เพื่อไม่คัดลอก |
| outputOffset | int | ออฟเซ็ตของบัฟเฟอร์ผลลัพธ์ |

### ค่าที่คืนกลับ

จำนวนไบต์ที่เขียน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)