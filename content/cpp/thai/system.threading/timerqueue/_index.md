---
title: TimerQueue
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: คิวที่จัดการวัตถุ Timer นี้เป็นเพียงการนำไปใช้เท่านั้น วัตถุ Timer ลงทะเบียนด้วยตนเอง คุณไม่จำเป็นต้องทำเช่นนั้นเพื่อใช้งาน – ใช้ API ของคลาส Timer แทน นี่เป็นประเภท singleton ที่จัดการหน่วยความจำโดยฟังก์ชันการเข้าถึง คุณไม่ควรสร้างอินสแตนซ์ของมันโดยตรง
type: docs
weight: 261
url: /th/system.threading/timerqueue/
---
## TimerQueue คลาส

คิวที่จัดการวัตถุ [Timer](../timer/) นี้เป็นเพียงการนำไปใช้เท่านั้น วัตถุ [Timer](../timer/) ลงทะเบียนด้วยตนเอง คุณไม่จำเป็นต้องทำเช่นนั้นเพื่อใช้งาน – ใช้ API ของคลาส [Timer](../timer/) แทน นี่เป็นประเภท singleton ที่จัดการหน่วยความจำโดยฟังก์ชันการเข้าถึง คุณไม่ควรสร้างอินสแตนซ์ของมันโดยตรง

```cpp
class TimerQueue
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | ลงทะเบียนตัวจับเวลาในคิว |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | ลบตัวจับเวลาออกจากคิว |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton ของการทำงาน |
| static void [JoinWorkerThread](./joinworkerthread/)() | เชื่อมต่อกับเธรด worker. รอคอยอย่างไม่มีที่สิ้นสุดหากจำเป็น |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | ไม่มีการคัดลอก |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | ไม่มีการคัดลอก |
## ดูเพิ่มเติม

* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)