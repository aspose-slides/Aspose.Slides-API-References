---
title: "System::Threading::Tasks"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 1015
url: /th/system.threading.tasks/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Parallel](./parallel/) | ให้การสนับสนุนการวนลูปขนานและโซน |
| [ParallelLoopResult](./parallelloopresult/) | ให้สถานะการเสร็จสมบูรณ์ของลูป [Parallel](./parallel/) |
| [ParallelOptions](./paralleloptions/) | เก็บตัวเลือกที่กำหนดการทำงานของเมธอดบนคลาส [Parallel](./parallel/) |
| [ResultTask](./resulttask/) | การพิเศษของ [Task](./task/) ที่คืนค่าผลลัพธ์เมื่อเสร็จสิ้น |
| [ResultValueTask](./resultvaluetask/) | แสดงถึงประเภทที่คล้ายกับงานแบบไฮบริดที่สามารถห่อหุ้มค่าผลลัพธ์โดยตรงหรือ ResultTask<T> ได้ |
| [Task](./task/) | แสดงถึงการทำงานแบบอะซิงโครนัสที่สามารถรอคอยและประสานกับงานอื่นได้ |
| [TaskScheduler](./taskscheduler/) | แสดงถึงอ็อบเจ็กต์ที่จัดการงานระดับล่างของการคิวงานลงบนเธรด |
| [ValueTask](./valuetask/) | ให้ผลลัพธ์ที่รอคอยได้ของการทำงานแบบอะซิงโครนัส |

## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | สร้างงานที่เสร็จสิ้นหลังจากความล่าช้าของเวลา |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | สร้างงานที่เสร็จสิ้นหลังจากความล่าช้าของเวลาและสามารถยกเลิกได้ |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | สร้างงานที่เสร็จสิ้นเนื่องจากการยกเลิกด้วยโทเคนที่ระบุ |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | สร้างงานที่เสร็จสิ้นด้วยข้อยกเว้นที่ระบุ |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | สร้างงานที่เสร็จสิ้นด้วยข้อยกเว้นและประเภทผลลัพธ์ที่ระบุ |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | สร้างงานที่เสร็จสมบูรณ์สำเร็จด้วยผลลัพธ์ที่ระบุ |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | คิวงานที่ระบุให้ทำงานบนพูลเธรดและคืนฮานด์ล์ [Task](./task/) สำหรับงานนั้น |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | คิวงานที่ระบุให้ทำงานบนพูลเธรดและคืนฮานด์ล์ [Task](./task/) สำหรับงานนั้น |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | คิวงานที่ระบุให้ทำงานบนพูลเธรดและคืนพร็อกซี่สำหรับ [Task](./task/) ที่ฟังก์ชันส่งกลับ |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | คิวงานที่ระบุให้ทำงานบนพูลเธรดและคืนฮานด์ล์ Task<TResult> สำหรับงานนั้น |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | รอให้วัตถุ [Task](./task/) ทั้งหมดที่ให้มาสำเร็จการดำเนินการ |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | รอให้วัตถุ [Task](./task/) ทั้งหมดที่ให้มาสำเร็จการดำเนินการ |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | รอให้วัตถุ [Task](./task/) ใดๆ ที่ให้มาสำเร็จการดำเนินการ |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | รอให้วัตถุ [Task](./task/) ใดๆ ที่ให้มาสำเร็จการดำเนินการ |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | สร้างงานที่เสร็จเมื่อทุกงานที่ให้มาสำเร็จ |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | สร้างงานที่เสร็จเมื่อทุกงานที่ให้มาสำเร็จ |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | สร้างงานที่เสร็จเมื่อทุกงานที่ให้มาสำเร็จ |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | สร้างงานที่เสร็จเมื่อทุกงานที่ให้มาสำเร็จ |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | สร้างงานที่เสร็จเมื่อใดก็ตามที่งานใดงานหนึ่งที่ให้มาสำเร็จ |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | สร้างงานที่เสร็จเมื่อใดก็ตามที่งานใดงานหนึ่งที่ให้มาสำเร็จ |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | สร้างงานที่เสร็จเมื่อใดก็ตามที่งานใดงานหนึ่งที่ให้มาสำเร็จ |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | สร้างงานที่เสร็จเมื่อใดก็ตามที่งานใดงานหนึ่งที่ให้มาสำเร็จ |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | สร้างงานที่รอคอยได้ซึ่งให้การทำงานแบบอะซิงโครนัสกลับสู่บริบทปัจจุบันเมื่อรอคอย |

## อีนัม

| อีนัม | คำอธิบาย |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |