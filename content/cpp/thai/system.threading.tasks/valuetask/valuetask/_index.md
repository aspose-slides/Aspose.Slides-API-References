---
title: ValueTask()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้าง ValueTask ที่ว่างเปล่าและไม่ได้กำหนดค่า.
type: docs
weight: 1
url: /th/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() คอนสตรัคเตอร์

สร้าง [ValueTask](../) ที่ว่างเปล่าและไม่ได้กำหนดค่า.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## หมายเหตุ



งานยังไม่เสร็จสมบูรณ์และไม่มีผลลัพธ์ การพยายามดึงผลลัพธ์จะทำให้เกิดข้อยกเว้น. 

## ValueTask::ValueTask(const TaskPtr\&) คอนสตรัคเตอร์


สร้าง [ValueTask](../) จาก shared pointer ที่อ้างอิงถึง [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | งานที่ห่อหุ้ม สามารถเป็น null สำหรับงานที่ว่าง |
## หมายเหตุ



[ValueTask](../) จะเป็นตัวแทนของสถานะของงานที่ให้มา. 

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* คลาส [ValueTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)