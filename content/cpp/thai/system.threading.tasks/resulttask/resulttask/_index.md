---
title: ResultTask()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้าง ResultTask ด้วยฟังก์ชันที่คืนค่าผลลัพธ์
type: docs
weight: 1
url: /th/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructor

สร้าง [ResultTask](../) ด้วยฟังก์ชันที่คืนค่าผลลัพธ์

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | ฟังก์ชันที่จะทำงานแบบอะซิงโครนัสและคืนค่าผลลัพธ์ |

## ResultTask::ResultTask() constructor

การใช้งานภายใน ไม่สำหรับโค้ดของผู้ใช้

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## หมายเหตุ

คอนสตรัคเตอร์ภายในสำหรับสร้างงานผลลัพธ์ที่ไม่ได้กำหนดค่าเริ่มต้น

## ResultTask::ResultTask(const T\&) constructor

คอนสตรัคเตอร์ภายในสำหรับสร้างงานผลลัพธ์ที่มีผลลัพธ์ที่ระบุ

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## ดูเพิ่มเติม

* คลาส [Func](../../../system/func/)
* คลาส [ResultTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)