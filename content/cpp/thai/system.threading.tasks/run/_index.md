---
title: Run()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: จัดคิวงานที่ระบุให้ทำงานบน thread pool และคืนตัวจัดการ Task สำหรับงานนั้น.
type: docs
weight: 157
url: /th/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) function

จัดคิวงานที่ระบุให้ทำงานบน thread pool และคืนตัวจัดการ [Task](../task/) สำหรับงานนั้น

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | งานที่ต้องทำอย่างไม่ประสานกัน |

### ค่าที่ส่งคืน

[Task](../task/) ที่เป็นตัวแทนของงานที่ถูกจัดคิวให้ทำใน thread pool

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) function

จัดคิวงานที่ระบุให้ทำงานบน thread pool และคืนตัวจัดการ [Task](../task/) สำหรับงานนั้น

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | งานที่ต้องทำอย่างไม่ประสานกัน |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | โทเค็นยกเลิกที่สามารถใช้ยกเลิกงานหากยังไม่ได้เริ่ม |

### ค่าที่ส่งคืน

[Task](../task/) ที่เป็นตัวแทนของงานที่ถูกจัดคิวให้ทำใน thread pool

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) function

จัดคิวงานที่ระบุให้ทำงานบน thread pool และคืนพร็อกซี่สำหรับ [Task](../task/) ที่ฟังก์ชันส่งคืน

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | งานที่ต้องทำอย่างไม่ประสานกัน ซึ่งส่งคืน [Task](../task/) |

### ค่าที่ส่งคืน

[Task](../task/) ที่เป็นตัวแทนของพร็อกซี่สำหรับ [Task](../task/) ที่ฟังก์ชันส่งคืน

## System::Threading::Tasks::Run(const Func\<TResult\>\&) function

จัดคิวงานที่ระบุให้ทำงานบน thread pool และคืนตัวจัดการ Task<TResult> สำหรับงานนั้น

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ชนิดของผลลัพธ์ที่งานส่งคืน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | งานที่ต้องทำอย่างไม่ประสานกัน |

### ค่าที่ส่งคืน

Task<TResult> ที่เป็นตัวแทนของงานที่ถูกจัดคิวให้ทำใน thread pool

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)