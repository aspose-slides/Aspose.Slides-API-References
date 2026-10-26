---
title: CancellationToken
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กระจายการแจ้งเตือนว่าการดำเนินการควรจะถูกยกเลิก คลาสนี้ให้กลไกสำหรับการยกเลิกแบบร่วมมือระหว่างเธรด โดยอนุญาตให้เธรดหนึ่งแจ้งให้เธรดอื่นทราบว่าการดำเนินการควรจะถูกยกเลิก
type: docs
weight: 14
url: /th/system.threading/cancellationtoken/
---
## CancellationToken คลาส

กระจายการแจ้งเตือนว่าควรยกเลิกการดำเนินการ คลาสนี้ให้กลไกสำหรับการยกเลิกแบบร่วมมือระหว่างเธรด โดยให้เธรดหนึ่งแจ้งให้เธรดอื่นทราบว่าควรยกเลิกการดำเนินการ

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | คอนสตรัคเตอร์เริ่มต้น. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | ตรวจสอบว่าโทเคนนี้สามารถอยู่ในสถานะยกเลิกได้หรือไม่. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | ตรวจสอบว่ามีการร้องขอยกเลิกสำหรับโทเคนนี้หรือไม่. |
| static [CancellationToken](./) [get_None](./get_none/)() | ส่งคืนค่า [System::Threading::CancellationToken](./) ที่ว่าง. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | ลงทะเบียน callback ที่จะเรียกเมื่อมีการร้องขอยกเลิก. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | โยน OperationCanceledException หากมีการร้องขอยกเลิก. |
## หมายเหตุ



[CancellationToken](./) สามารถยกเลิกได้ผ่าน [CancellationTokenSource](../cancellationtokensource/) ที่เชื่อมโยงกับมันเท่านั้น. 

## ดูเพิ่มเติม

* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)