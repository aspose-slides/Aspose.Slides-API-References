---
title: Task()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้าง Task พร้อมการกระทำเพื่อดำเนินการ
type: docs
weight: 1
url: /th/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) คอนสตรัคเตอร์

สร้าง [Task](../) พร้อมกับการกระทำเพื่อดำเนินการ.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | การกระทำที่จะดำเนินการแบบอะซิงโครนัส |

## Task::Task(const Action<>\&, const CancellationToken\&) คอนสตรัคเตอร์

สร้าง [Task](../) ด้วยการกระทำและโทเคนการยกเลิก.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | การกระทำที่จะดำเนินการแบบอะซิงโครนัส |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเคนสำหรับตรวจสอบคำขอยกเลิก |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) คอนสตรัคเตอร์

สร้าง [Task](../) ด้วยการกระทำที่มีสถานะและอ็อบเจกต์สถานะ.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | การกระทำที่จะดำเนินการ (รับอ็อบเจกต์สถานะ) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อ็อบเจกต์สถานะที่กำหนดโดยผู้ใช้ซึ่งส่งให้การกระทำ |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) คอนสตรัคเตอร์

สร้าง [Task](../) ด้วยการกระทำที่มีสถานะ, สถานะ, และโทเคนการยกเลิก.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | การกระทำที่จะดำเนินการ (รับอ็อบเจกต์สถานะ) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อ็อบเจกต์สถานะที่กำหนดโดยผู้ใช้ซึ่งส่งให้การกระทำ |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | โทเคนสำหรับตรวจสอบคำขอยกเลิก |

## Task::Task() คอนสตรัคเตอร์

คอนสตรัคเตอร์ภายในสำหรับสร้างงานที่ยังไม่ได้กำหนดค่า.

```cpp
System::Threading::Tasks::Task::Task()
```

## ดูเพิ่มเติม

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Task](../)
* คลาส [CancellationToken](../../../system.threading/cancellationtoken/)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)