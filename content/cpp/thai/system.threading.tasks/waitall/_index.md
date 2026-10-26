---
title: WaitAll()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอให้วัตถุ Task ทั้งหมดที่ระบุทำงานจนเสร็จสิ้น
type: docs
weight: 170
url: /th/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) ฟังก์ชัน

รอให้วัตถุ [Task](../task/) ทั้งหมดที่ระบุทำงานเสร็จสิ้น

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | อาร์เรย์ของอินสแตนซ์ [Task](../task/) ที่ต้องรอ |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) ที่จะสังเกตขณะรอให้งานเสร็จสิ้น |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) ฟังก์ชัน

รอให้วัตถุ [Task](../task/) ทั้งหมดที่ระบุทำงานเสร็จสิ้น

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | อาร์เรย์ของอินสแตนซ์ [Task](../task/) ที่ต้องรอ |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)