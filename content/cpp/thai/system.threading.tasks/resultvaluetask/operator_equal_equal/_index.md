---
title: operator==()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตัวดำเนินการเท่ากันสำหรับ ResultValueTask.
type: docs
weight: 131
url: /th/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const method

ตัวดำเนินการเท่ากันสำหรับ [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | The other [ResultValueTask](../) to compare with this instance. |

### ค่าที่ส่งกลับ

bool True หากงานทั้งสองมีค่า result เท่ากันหรืออ้างอิงถึงงานพื้นฐานเดียวกัน; มิฉะนั้น false.

## หมายเหตุ

ถ้าอินสแตนซ์ใดอินสแตนซ์หนึ่งมีค่า result โดยตรง จะเปรียบเทียบค่าดังกล่าวโดยตรง มิฉะนั้นจะเปรียบเทียบตัวชี้ของงานพื้นฐาน. 

## ดูเพิ่มเติม

* คลาส [ResultValueTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)