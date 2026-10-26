---
title: TransformBlock()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประมวลผลบล็อกของข้อมูลและคัดลอกข้อมูลไปยังอาร์เรย์ผลลัพธ์.
type: docs
weight: 66
url: /th/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) เมธอด

ประมวลผลบล็อกของข้อมูลและคัดลอกข้อมูลไปยังอาเรย์ผลลัพธ์.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลจาก |
| inputOffset | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| inputCount | int | จำนวนไบต์ที่ต้องประมวลผล |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ผลลัพธ์เพื่อคัดลอกข้อมูลเข้า; nullptr เพื่อไม่ทำการคัดลอก |
| outputOffset | int | ออฟเซ็ตของบัฟเฟอร์ผลลัพธ์ |

### ค่าที่คืนกลับ

จำนวนไบต์ที่เขียน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [HashAlgorithm](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)