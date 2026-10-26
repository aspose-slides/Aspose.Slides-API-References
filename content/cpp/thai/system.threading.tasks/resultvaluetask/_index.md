---
title: ResultValueTask
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงประเภทที่คล้ายงานแบบไฮบริดที่สามารถห่อหุ้มค่าผลลัพธ์โดยตรงหรือ ResultTask<T> ได้
type: docs
weight: 53
url: /th/system.threading.tasks/resultvaluetask/
---
## ResultValueTask คลาส


เป็นประเภทที่คล้ายงานแบบไฮบริดที่สามารถห่อหุ้มค่าผลลัพธ์โดยตรงหรือ ResultTask<T> ได้.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของผลลัพธ์ที่งานสร้างขึ้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | แปลง [ResultValueTask](./) นี้เป็น shared pointer ไปยัง ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | กำหนดค่า awaiter สำหรับงานนี้. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | กำหนดว่าตัวอย่างนี้เท่ากับตัวอย่าง [ResultValueTask](./) อีกตัวหรือไม่. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | กำหนดว่าตัวอย่างนี้เท่ากับอ็อบเจกต์อื่นหรือไม่. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุเท่ากันหรือไม่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | รับค่าที่บ่งชี้ว่าทาสก์เสร็จสิ้นเนื่องจากถูกยกเลิกหรือไม่. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | รับค่าที่บ่งชี้ว่าทาสก์เสร็จสิ้นหรือไม่. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | รับค่าที่บ่งชี้ว่าทาสก์เสร็จสิ้นอย่างประสบผลสำเร็จหรือไม่. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | รับค่าที่บ่งชี้ว่าทาสก์เสร็จสิ้นเนื่องจากข้อยกเว้นที่ไม่ได้จัดการหรือไม่. |
| T [get_Result](./get_result/)() | รับผลลัพธ์ของทาสก์ที่เสร็จแล้ว. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | รับ awaiter สำหรับทาสก์นี้เพื่อรองรับการแสดงออก await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นเทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเทียบเคียงกับ operator 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกรายการใด ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคอนสตรัคเตอร์สำเนาสำหรับคลาสตักย่อย. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | ตัวดำเนินการไม่เท่ากับสำหรับ [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกรายการใด ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคอนสตรัคเตอร์สำเนาสำหรับคลาสตักย่อย. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | ตัวดำเนินการเท่ากับสำหรับ [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
|  [ResultValueTask](./resultvaluetask/)() | สร้าง [ResultValueTask](./) ที่ว่างและยังไม่ได้กำหนดค่า. |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | สร้าง [ResultValueTask](./) ที่เสร็จสมบูรณ์ด้วยผลลัพธ์ที่ระบุ. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | สร้าง [ResultValueTask](./) จาก shared pointer ไปยัง ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## หมายเหตุ


[ResultValueTask](./) รวมประโยชน์ของ [ValueTask](../valuetask/) (การจัดสรรที่น้อยลงสำหรับผลลัพธ์แบบ synchronous) กับความสามารถในการห่อหุ้มอ็อบเจกต์ ResultTask<T> ที่มีอยู่แล้ว. มันให้ interface ที่สามารถ await ได้และเมธอดตรวจสอบสถานะของทาสก์หลายประเภท. 
## ดูเพิ่มเติม

* คลาส [IEquatable](../../system/iequatable/)
* เนมสเปซ [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)