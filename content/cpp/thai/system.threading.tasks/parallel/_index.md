---
title: Parallel
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้การสนับสนุนสำหรับลูปและโซนแบบขนาน.
type: docs
weight: 1
url: /th/system.threading.tasks/parallel/
---
## คลาส Parallel

Provides support for parallel loops and regions.

```cpp
class Parallel
```

## เมธอด

| Method | Description |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | ดำเนินการ foreach บน IEnumerable ที่การวนซ้ำอาจทำงานแบบขนาน |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | ดำเนินการ foreach บน IEnumerable ที่การวนซ้ำอาจทำงานแบบขนาน |
## หมายเหตุ

คลาสนี้ให้เมธอดสำหรับการดำเนินการแบบขนานของลูปและการทำงาน. 
## ดูเพิ่มเติม

* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)