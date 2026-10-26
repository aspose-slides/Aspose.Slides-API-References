---
title: get_Current()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ดึงบริบทการซิงโครไนซ์สำหรับเธรดปัจจุบัน.
type: docs
weight: 40
url: /th/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() เมธอด


ดึงบริบทการซิงโครไนซ์สำหรับเธรดปัจจุบัน.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### ค่าที่ส่งคืน

SharedPtr<SynchronizationContext> ตัวชี้แบบแชร์ไปยังบริบทการซิงโครไนซ์ของเธรดปัจจุบัน.
## หมายเหตุ



คืนค่า null หากไม่มีบริบทการซิงโครไนซ์ที่ตั้งค่าสำหรับเธรดปัจจุบัน. 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [SynchronizationContext](../)
* เนมส페ซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)