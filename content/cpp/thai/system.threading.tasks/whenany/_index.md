---
title: WhenAny()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างงานที่เสร็จเมื่อใดก็ได้เมื่อหนึ่งในงานที่จัดเตรียมสำเร็จ
type: docs
weight: 209
url: /th/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) ฟังก์ชัน

สร้างงานที่เสร็จเมื่อใดก็ได้เมื่อหนึ่งในงานที่จัดเตรียมสำเร็จ

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | งานที่ต้องรอให้เสร็จสิ้น |

### ค่าที่ส่งกลับ

งานที่แสดงถึงการเสร็จของหนึ่งในงานที่จัดเตรียมไว้

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) ฟังก์ชัน

สร้างงานที่เสร็จเมื่อใดก็ได้เมื่อหนึ่งในงานที่จัดเตรียมสำเร็จ

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | งานที่ต้องรอให้เสร็จสิ้น |

### ค่าที่ส่งกลับ

งานที่แสดงถึงการเสร็จของหนึ่งในงานที่จัดเตรียมไว้

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) ฟังก์ชัน

สร้างงานที่เสร็จเมื่อใดก็ได้เมื่อหนึ่งในงานที่จัดเตรียมสำเร็จ

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ประเภทของผลลัพธ์ของงานที่เสร็จสมบูรณ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | งานที่ต้องรอให้เสร็จสิ้น |

### ค่าที่ส่งกลับ

งานที่ส่งคืนงานที่แรกที่เสร็จเมื่อใดก็ได้เมื่อมีงานใดงานหนึ่งเสร็จสิ้น

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) ฟังก์ชัน

สร้างงานที่เสร็จเมื่อใดก็ได้เมื่อหนึ่งในงานที่จัดเตรียมสำเร็จ

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TResult | ประเภทของผลลัพธ์ของงานที่เสร็จสมบูรณ์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | งานที่ต้องรอให้เสร็จสิ้น |

### ค่าที่ส่งกลับ

งานที่ส่งคืนงานที่แรกที่เสร็จเมื่อใดก็ได้เมื่อมีงานใดงานหนึ่งเสร็จสิ้น

## ดูเพิ่มเติม

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)