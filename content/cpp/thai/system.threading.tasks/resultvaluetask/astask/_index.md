---
title: AsTask()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลง ResultValueTask นี้เป็น shared pointer ไปยัง ResultTask<T>.
type: docs
weight: 79
url: /th/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const เมธอด


แปลง [ResultValueTask](../) นี้เป็น shared pointer ไปยัง ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### ค่าที่ส่งกลับ

RTaskPtr<T> shared pointer ไปยัง ResultTask<T> ที่เป็นตัวแทนของการดำเนินการนี้.
## หมายเหตุ



หาก [ResultValueTask](../) มีผลลัพธ์โดยตรง จะสร้างงานที่เสร็จสมบูรณ์พร้อมผลลัพธ์นั้น หากมีงานอยู่ จะคืนค่า shared pointer ไปยังงานนั้น. 

## ดูเพิ่มเติม

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* คลาส [ResultValueTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)