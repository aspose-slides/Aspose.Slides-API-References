---
title: Task
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงการดำเนินการแบบอะซิงโครนัสที่สามารถรอได้และประกอบกับงานอื่น ๆ
type: docs
weight: 66
url: /th/system.threading.tasks/task/
---
## คลาส Task


Represents an asynchronous operation that can be awaited and composed with other tasks.

```cpp
class Task : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | ทำให้งานเริ่มทำงานบนตัวจัดเวลา. |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | เพิ่มการดำเนินการต่อที่ทำเมื่อเสร็จสิ้น. |
| void [Cancel](./cancel/)() | ทำเครื่องหมายงานว่าถูกยกเลิกและจบงาน. |
| void [Complete](./complete/)() | ทำเครื่องหมายงานว่าเสร็จสมบูรณ์และจบงาน. |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | กำหนดวิธีการรอ (await) งานนี้จะทำงานอย่างไรเกี่ยวกับการจับบริบท. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | สร้างการดำเนินการต่อที่จะทำเมื่องานเสร็จสมบูรณ์. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | สร้างการดำเนินการต่อที่จะทำเมื่องานเสร็จสมบูรณ์. |
| void [Deactivate](./deactivate/)() | ปิดการทำงานของงานบนตัวจัดเวลาปัจจุบันหากมี. |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรที่เกี่ยวข้องกับงาน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหากใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหากใด ๆ รวมถึง NaN ด้วย. |
| void [Execute](./execute/)() | ดำเนินการฟังก์ชันของงาน. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | รับอ็อบเจ็กต์สถานะที่กำหนดโดยผู้ใช้ที่เกี่ยวข้องกับงาน. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | รับงานที่เสร็จสมบูรณ์ (singleton) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | รับ ID สำหรับงาน. |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | รับว่าการทำงานเสร็จเนื่องจากการยกเลิกหรือไม่. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | รับว่างานได้เสร็จหรือไม่. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | รับว่าการทำงานเสร็จเนื่องจากข้อยกเว้นที่ไม่ได้จัดการหรือไม่. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | รับตัวจัดเวลาที่เกี่ยวข้องกับงานนี้. |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | รับสถานะปัจจุบันของงาน. |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | รับ awaiter สำหรับงานนี้เพื่อใช้กับ Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นแบบจำลองของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริงๆ ไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำแนกพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำแนกพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแชร์โดยค่าที่ระบุ. |
| void [RunSynchronously](./runsynchronously/)() | เรียกงานอย่างประสานกันบนเธรดปัจจุบัน. |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | เรียกงานอย่างประสานกันโดยใช้ตัวจัดเวลาที่ระบุ. |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | ตั้งค่าฟังก์ชันภายในที่จะดำเนินการ. |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | ตั้งค่าตัวจัดเวลาที่เกี่ยวข้องกับงานนี้. |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | ตั้งค่าสถานะของงาน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [Start](./start/)() | เริ่มการดำเนินการของงานโดยใช้ตัวจัดเวลาเริ่มต้น. |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | เริ่มการดำเนินการของงานโดยใช้ตัวจัดเวลาที่ระบุ. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&) | สร้าง [Task](./) ด้วยการดำเนินการที่จะทำ. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | สร้าง [Task](./) ด้วยการดำเนินการและโทเค็นยกเลิก. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | สร้าง [Task](./) ด้วยการดำเนินการที่มีสถานะและอ็อบเจ็กต์สถานะ. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | สร้าง [Task](./) ด้วยการดำเนินการที่มีสถานะ, สถานะ, และโทเค็นยกเลิก. |
|  [Task](./task/)() | คอนสตรัคเตอร์ภายในสำหรับสร้างงานที่ยังไม่ได้กำหนดค่า. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | รอให้งานเสร็จสมบูรณ์พร้อมการสนับสนุนการยกเลิก. |
| void [Wait](./wait/)() | รอให้งานเสร็จสมบูรณ์. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
|  [~Task](./~task/)() | ตัวทำลาย. |
## การกำหนดประเภท

| การกำหนดประเภท | คำอธิบาย |
| --- | --- |
| [FunctionT](./functiont/) | การทำงานภายใน. ไม่สำหรับโค้ดผู้ใช้. |
## หมายเหตุ


ให้การทำงานของ C++ ที่คล้ายกับ [System.Threading.Tasks.Task](./) ใน .NET, รองรับการยกเลิก, การดำเนินการต่อ, และรูปแบบ async/await
## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)