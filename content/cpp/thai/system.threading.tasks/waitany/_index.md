---
title: WaitAny()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รอให้วัตถุ Task ใด ๆ ที่ระบุเสร็จสิ้นการทำงาน.
type: docs
weight: 183
url: /th/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) ฟังก์ชัน

รอให้วัตถุ [Task](../task/) ใด ๆ ที่ระบุเสร็จสิ้นการทำงาน.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | อาร์เรย์ของ [Task](../task/) อินสแตนซ์ที่ต้องรอ |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) ที่สังเกตในขณะที่รอให้ภารกิจเสร็จสิ้น |

### ค่าที่ส่งกลับ

ดัชนีของภารกิจที่เสร็จในอาเรย์ tasks

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) ฟังก์ชัน

รอให้วัตถุ [Task](../task/) ใด ๆ ที่ระบุเสร็จสิ้นการทำงาน.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | อาร์เรย์ของ [Task](../task/) อินสแตนซ์ที่ต้องรอ |

### ค่าที่ส่งกลับ

ดัชนีของภารกิจที่เสร็จในอาเรย์ tasks

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* คลาส [CancellationToken](../../system.threading/cancellationtoken/)
* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)