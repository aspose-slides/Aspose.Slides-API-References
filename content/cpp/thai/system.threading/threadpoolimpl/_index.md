---
title: ThreadPoolImpl
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: ข้อมูลภายในของ thread pool. นี่เป็นประเภท singleton ที่การจัดการหน่วยความจำทำโดยฟังก์ชันการเข้าถึง. คุณไม่ควรสร้างอินสแตนซ์โดยตรง.
type: docs
weight: 235
url: /th/system.threading/threadpoolimpl/
---
## ThreadPoolImpl คลาส

[Thread](../thread/) pool internal data. นี่เป็นชนิด singleton ที่การจัดการหน่วยความจำทำโดยฟังก์ชันการเข้าถึง. คุณไม่ควรสร้างอินสแตนซ์โดยตรง.

```cpp
class ThreadPoolImpl
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | ดึงจำนวนเธรดที่พร้อมใช้งาน |
| static **bool**\& [GetInitialized](./getinitialized/)() | ดึงสถานะการเริ่มต้นของ singleton |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | ดึงจำนวนสูงสุดของเธรดพร้อมกัน |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | ดึงจำนวนขั้นต่ำของเธรดที่สร้างโดย pool |
| void [JoinAll](./joinall/)() | เข้าร่วมเธรดทั้งหมดที่เป็นของ pool. รออย่างไม่มีที่สิ้นสุด |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | เพิ่มรายการงานลงในคิว |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | ตั้งค่าจำนวนเธรดที่เป็นของ pool |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | ตั้งค่าจำนวนขั้นต่ำของเธรดที่เป็นของ pool |
|  [ThreadPoolImpl](./threadpoolimpl/)() | คอนสตรัคเตอร์ |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | ดีสตรัคเตอร์. เข้าร่วมเธรดทั้งหมดหากยังไม่ได้ยุติ |

## ดูเพิ่มเติม

* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)