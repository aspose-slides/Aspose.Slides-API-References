---
title: TransformFinalBlock()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประมวลผลบล็อกสุดท้ายของข้อมูลและคำนวณแฮช.
type: docs
weight: 79
url: /th/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) เมธอด

ประมวลผลบล็อกสุดท้ายของข้อมูลและคำนวณแฮช.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลจาก. |
| inputOffset | int | ออฟเซ็ตบัฟเฟอร์อินพุต. |
| inputCount | int | จำนวนไบต์ที่ต้องประมวลผล. |

### Return Value

แฮชที่คำนวณสำหรับลำดับข้อมูลทั้งหมด.

## See Also

* ชนิดนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [HashAlgorithm](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)