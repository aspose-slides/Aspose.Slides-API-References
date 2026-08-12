---
title: ContinueWith()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้าง continuation ที่ทำงานเมื่อ task เสร็จสมบูรณ์.
type: docs
weight: 118
url: /th/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) เมธอด


สร้าง continuation ที่จะทำงานเมื่อ task เสร็จสิ้น

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action ที่จะดำเนินการเมื่อ task นี้เสร็จสิ้น |

### ค่าที่ส่งคืน

TaskPtr งานใหม่ที่เป็นตัวแทนของ continuation

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) เมธอด


สร้าง continuation ที่จะทำงานเมื่อ task เสร็จสิ้น

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ชนิดของผลลัพธ์ของ task |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Function ที่จะรับผลลัพธ์เมื่อ task นี้เสร็จสิ้น |

### ค่าที่ส่งคืน

RTaskPtr งานใหม่ที่เป็นตัวแทนของ continuation

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)