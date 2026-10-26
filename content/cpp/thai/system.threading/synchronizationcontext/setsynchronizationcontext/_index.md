---
title: SetSynchronizationContext()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าบริบทการซิงโครไนซ์สำหรับเธรดปัจจุบัน.
type: docs
weight: 53
url: /th/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) เมธอด


ตั้งค่าบริบทการซิงโครไนซ์สำหรับเธรดปัจจุบัน.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | บริบทการซิงโครไนซ์ที่ต้องตั้งค่าให้กับเธรดปัจจุบัน. |
## หมายเหตุ



การส่ง nullptr จะล้างบริบทการซิงโครไนซ์สำหรับเธรดปัจจุบัน. 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [SynchronizationContext](../)
* เนมสเปซ [System::Threading](../../)
* Library [Aspose.Slides](../../../)