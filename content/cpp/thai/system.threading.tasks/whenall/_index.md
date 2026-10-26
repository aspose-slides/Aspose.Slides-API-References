---
title: WhenAll()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: สร้างงานที่เสร็จสมบูรณ์เมื่อทุกงานที่ระบุทั้งหมดเสร็จสิ้น.
type: docs
weight: 196
url: /th/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) function

สร้างงานที่เสร็จเมื่อทุกงานที่ระบุทั้งหมดเสร็จสมบูรณ์

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | งานที่รอให้เสร็จสมบูรณ์ |

### ค่าที่ส่งคืน

งานที่แสดงถึงการเสร็จสมบูรณ์ของทุกงานที่ระบุ

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function

สร้างงานที่เสร็จเมื่อทุกงานที่ระบุทั้งหมดเสร็จสมบูรณ์

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | งานที่รอให้เสร็จสมบูรณ์ |

### ค่าที่ส่งคืน

งานที่แสดงถึงการเสร็จสมบูรณ์ของทุกงานที่ระบุ

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function

สร้างงานที่เสร็จเมื่อทุกงานที่ระบุทั้งหมดเสร็จสมบูรณ์

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ประเภทของผลลัพธ์ของงานที่เสร็จสมบูรณ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | งานที่รอให้เสร็จสมบูรณ์ |

### ค่าที่ส่งคืน

งานที่ส่งกลับอาร์เรย์ของผลลัพธ์ทั้งหมดเมื่อทุกงานเสร็จสมบูรณ์

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function

สร้างงานที่เสร็จเมื่อทุกงานที่ระบุทั้งหมดเสร็จสมบูรณ์

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ประเภทของผลลัพธ์ของงานที่เสร็จสมบูรณ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | งานที่รอให้เสร็จสมบูรณ์ |

### ค่าที่ส่งคืน

งานที่ส่งกลับอาร์เรย์ของผลลัพธ์ทั้งหมดเมื่อทุกงานเสร็จสมบูรณ์

## ดูเพิ่มเติม

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* คลาส [IEnumerable](../../system.collections.generic/ienumerable/)
* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)