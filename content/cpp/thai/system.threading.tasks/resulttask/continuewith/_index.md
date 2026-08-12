---
title: ContinueWith()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างการต่อเนื่องที่ทำงานเมื่อผลลัพธ์ของงานเสร็จสมบูรณ์
type: docs
weight: 40
url: /th/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) เมธอด

สร้างการต่อเนื่องที่ทำงานเมื่อผลลัพธ์ของงานเสร็จสมบูรณ์

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | การกระทำที่จะดำเนินการเมื่อ งานนี้เสร็จสิ้นและรับผลลัพธ์ของงานนี้ |

### ค่าที่ส่งคืน

TaskPtr งานใหม่ที่เป็นตัวแทนของการต่อเนื่อง

## หมายเหตุ

การกระทำต่อเนื่องรับ [ResultTask](../) นี้เพื่อเข้าถึงค่าผลลัพธ์

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) เมธอด

สร้างการต่อเนื่องที่ทำงานเมื่อผลลัพธ์ของงานเสร็จสมบูรณ์

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TNewResult | ประเภทของผลลัพธ์สำหรับการต่อเนื่องของงาน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | ฟังก์ชันเพื่อรับผลลัพธ์การต่อเนื่องเมื่อ งานนี้เสร็จสิ้นและรับผลลัพธ์ของงานนี้ |

### ค่าที่ส่งคืน

RTaskPtr งานใหม่ที่เป็นตัวแทนของการต่อเนื่อง

## หมายเหตุ

การทำงานต่อเนื่องรับ [ResultTask](../) นี้เพื่อเข้าถึงค่าผลลัพธ์

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) เมธอด

สร้างการต่อเนื่องที่ทำงานเมื่อ งานเสร็จสมบูรณ์

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | การกระทำที่จะดำเนินการเมื่อ งานนี้เสร็จสิ้น |

### ค่าที่ส่งคืน

TaskPtr งานใหม่ที่เป็นตัวแทนของการต่อเนื่อง

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) เมธอด

สร้างการต่อเนื่องที่ทำงานเมื่อ งานเสร็จสมบูรณ์

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ประเภทของผลลัพธ์ของงาน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | ฟังก์ชันเพื่อรับผลลัพธ์เมื่อ งานนี้เสร็จสิ้น |

### ค่าที่ส่งคืน

RTaskPtr งานใหม่ที่เป็นตัวแทนของการต่อเนื่อง

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)