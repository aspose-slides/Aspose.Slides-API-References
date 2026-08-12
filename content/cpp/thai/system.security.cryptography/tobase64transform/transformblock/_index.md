---
title: TransformBlock()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ประมวลผลบล็อกของข้อมูลและคัดลอกข้อมูลไปยังอาร์เรย์ผลลัพธ์.
type: docs
weight: 53
url: /th/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) เมธอด

ประมวลผลบล็อกของข้อมูลและคัดลอกข้อมูลไปยังอาร์เรย์ผลลัพธ์。

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลจาก. |
| inputOffset | **int32_t** | การชดเชยบัฟเฟอร์อินพุต. |
| inputCount | **int32_t** | จำนวนไบต์ที่ต้องประมวลผล. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ผลลัพธ์สำหรับคัดลอกข้อมูลเข้า; nullptr เพื่อไม่ทำการคัดลอก. |
| outputOffset | **int32_t** | การชดเชยบัฟเฟอร์ผลลัพธ์. |

### ค่าที่คืนกลับ

จำนวนไบต์ที่เขียน

## ดูเพิ่มเติม

* ประเภทกำหนด [ArrayPtr](../../../system/arrayptr/)
* คลาส [ToBase64Transform](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)