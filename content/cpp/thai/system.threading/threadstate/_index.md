---
title: ThreadState
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สถานะของเธรด.
type: docs
weight: 326
url: /th/system.threading/threadstate/
---
## ThreadState enum

สถานะของเธรด.

```cpp
enum ThreadState
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) กำลังทำงาน. |
| StopRequested | 1 | [Thread](../thread/) การหยุดถูกร้องขอ. |
| SuspendRequested | 2 | [Thread](../thread/) การระงับถูกร้องขอ. |
| Background | 4 | เธรดกำลังทำงานในพื้นหลัง. |
| Unstarted | 8 | [Thread](../thread/) ยังไม่ได้เริ่มต้น. |
| Stopped | 16 | [Thread](../thread/) ถูกหยุด. |
| WaitSleepJoin | 32 | [Thread](../thread/) กำลังรอการเข้าร่วม. |
| Suspended | 64 | [Thread](../thread/) ถูกระงับ. |
| AbortRequested | 128 | [Thread](../thread/) การยกเลิกถูกร้องขอ. |
| Aborted | 256 | [Thread](../thread/) ถูกยกเลิก. |

## ดูเพิ่ม

* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)