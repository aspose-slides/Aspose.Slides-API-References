---
title: CancellationTokenRegistration
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดงถึงการลงทะเบียนสำหรับ callback ของ cancellation token.
type: docs
weight: 27
url: /th/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration คลาส

แสดงถึงการลงทะเบียนสำหรับ callback ของ cancellation token

```cpp
class CancellationTokenRegistration
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Dispose](./dispose/)() | ทำลายการลงทะเบียนและลบ callback ออกจาก [CancellationTokenSource](../cancellationtokensource/) ที่เกี่ยวข้อง หลังจากเรียกเมธอดนี้ callback ที่ลงทะเบียนจะไม่ถูกเรียกใช้เมื่อ [CancellationTokenSource](../cancellationtokensource/) ที่เกี่ยวข้องถูกยกเลิก |
## หมายเหตุ

คลาสนี้อนุญาตให้ยกเลิกการลงทะเบียน callback จาก cancellation token เมื่อทำลายแล้ว มันจะลบ callback จาก [CancellationTokenSource](../cancellationtokensource/) ที่เกี่ยวข้อง คลาสนี้ไม่ควรถูกสร้างโดยตรง - มันถูกส่งคืนโดย [CancellationToken](../cancellationtoken/) วิธีการลงทะเบียน.

## ดูเพิ่มเติม

* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)