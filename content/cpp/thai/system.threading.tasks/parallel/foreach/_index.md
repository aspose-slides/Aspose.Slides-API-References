---
title: ForEach()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดำเนินการ foreach บน IEnumerable ที่การทำซ้ำอาจทำงานแบบขนาน
type: docs
weight: 1
url: /th/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) เมธอด

ดำเนินการ foreach บน IEnumerable ที่การทำซ้ำอาจทำงานแบบขนาน

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TSource | ประเภทของข้อมูลใน source |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | อ็อบเจกต์ที่กำหนดค่าพฤติกรรมของการดำเนินการนี้. |
| body | const [Action](../../../system/action/)\<TSource\>\& | เดลิเกตที่เรียกใช้หนึ่งครั้งต่อการทำซ้ำ. |

### ค่าที่ส่งกลับ

โครงสร้าง [ParallelLoopResult](../../parallelloopresult/) ที่บรรจุข้อมูลเกี่ยวกับส่วนที่ทำงานของลูปที่สำเร็จ

## หมายเหตุ

เมธอดนี้แบ่ง source enumerable และดำเนินการเดลิเกต body บนหลายเธรดพร้อมกัน

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) เมธอด

ดำเนินการ foreach บน IEnumerable ที่การทำซ้ำอาจทำงานแบบขนาน

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| TSource | ประเภทของข้อมูลใน source |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| body | const [Action](../../../system/action/)\<TSource\>\& | เดลิเกตที่เรียกใช้หนึ่งครั้งต่อการทำซ้ำ. |

### ค่าที่ส่งกลับ

โครงสร้าง [ParallelLoopResult](../../parallelloopresult/) ที่บรรจุข้อมูลเกี่ยวกับส่วนที่ทำงานของลูปที่สำเร็จ

## หมายเหตุ

ใช้ค่าเริ่มต้น [ParallelOptions](../../paralleloptions/) พร้อมการทำงานแบบขนานไม่จำกัดและไม่มีการยกเลิก

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [ParallelLoopResult](../../parallelloopresult/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)