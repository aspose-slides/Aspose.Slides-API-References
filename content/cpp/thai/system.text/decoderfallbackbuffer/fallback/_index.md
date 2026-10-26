---
title: Fallback()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำหน้าที่เป็นขั้นตอนสำรองข้อมูลจริง
type: docs
weight: 14
url: /th/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) เมธอด

ทำหน้าที่เป็นขั้นตอนสำรองข้อมูลจริง

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) ของไบต์รวมถึงไบต์ที่ตัวถอดรหัสไม่สามารถถอดรหัสได้ |
| index | int | [Index](../../../system/index/) ของไบต์ที่ทำให้เกิดข้อผิดพลาด |

### ค่าที่ส่งกลับ

คืนค่า true หากบัฟเฟอร์ทำการประมวลผลไบต์ที่ไม่รู้จัก, false หากบัฟเฟอร์ละเว้นพวกมัน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [DecoderFallbackBuffer](../)
* เนมส페ซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)