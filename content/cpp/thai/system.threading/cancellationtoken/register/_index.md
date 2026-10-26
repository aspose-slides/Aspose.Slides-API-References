---
title: Register()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ลงทะเบียน callback ที่จะถูกเรียกใช้เมื่อมีการขอยกเลิก
type: docs
weight: 40
url: /th/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const เมธอด

ลงทะเบียน callback ที่จะถูกเรียกใช้เมื่อมีการขอยกเลิก

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Action<> ที่จะดำเนินการเมื่อมีการขอยกเลิก |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [CancellationTokenRegistration](../../cancellationtokenregistration/) ที่สามารถใช้เพื่อยกเลิกการลงทะเบียน callback.

## หมายเหตุ

หากการยกเลิกได้ถูกขอแล้ว, callback จะถูกเรียกใช้โดยทันที.  

callback ควรสั้นและไม่บล็อกเนื่องจากจะถูกดำเนินการบนเธรดที่เรียก Cancel() บน [CancellationTokenSource](../../cancellationtokensource/).

## ดูเพิ่มเติม

* Typedef [Action](../../../system/action/)
* คลาส [CancellationTokenRegistration](../../cancellationtokenregistration/)
* คลาส [CancellationToken](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)