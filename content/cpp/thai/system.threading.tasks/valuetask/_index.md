---
title: ValueTask
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้ผลลัพธ์ที่สามารถรอได้จากการดำเนินการแบบอะซิงโครนัส.
type: docs
weight: 92
url: /th/system.threading.tasks/valuetask/
---
## ValueTask คลาส

ให้ผลลัพธ์ที่รอได้จากการดำเนินการแบบอะซิงโครนัส

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [TaskPtr](../../system/taskptr/) [AsTask](./astask/)() const | แปลง [ValueTask](./) นี้เป็น shared pointer ไปยัง [Task](../task/). |
| [Runtime::CompilerServices::ConfiguredValueTaskAwaitable](../../system.runtime.compilerservices/configuredvaluetaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | กำหนดค่า awaiter สำหรับงานนี้. |
| **bool** [Equals](./equals/)([ValueTask](./)) override | กำหนดว่าตัวอย่างนี้เท่ากับตัวอย่าง [ValueTask](./) อื่นหรือไม่. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | กำหนดว่าตัวอย่างนี้เท่ากับอ็อบเจกต์อื่นหรือไม่. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | กำหนดว่าค่าวัตถุปัจจุบันและวัตถุที่ระบุเท่ากันหรือไม่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ float แบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ double แบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | รับค่าที่บ่งบอกว่าหน้าที่เสร็จสมบูรณ์เนื่องจากถูกยกเลิกหรือไม่. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | รับค่าที่บ่งบอกว่างานได้เสร็จสมบูรณ์หรือไม่. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | รับค่าที่บ่งบอกว่างานเสร็จสมบูรณ์อย่างประสบความสำเร็จหรือไม่. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | รับค่าที่บ่งบอกว่างานเสร็จสมบูรณ์เนื่องจากข้อยกเว้นที่ไม่ได้จัดการหรือไม่. |
| [Runtime::CompilerServices::ValueTaskAwaiter](../../system.runtime.compilerservices/valuetaskawaiter/) [GetAwaiter](./getawaiter/)() const | รับ awaiter สำหรับงานนี้เพื่อสนับสนุนการใช้ await expression. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นตัวอย่างของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกประสงค์ของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| **bool** [operator!=](./operator_not_equal/)(const [ValueTask](./)\&) const | ตัวดำเนินการไม่เท่ากับสำหรับ [ValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTask](./)\&) const | ตัวดำเนินการเท่ากับสำหรับ [ValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบ shared ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบ shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบ shared และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
|  [ValueTask](./valuetask/)() | สร้าง [ValueTask](./) ที่ว่างและยังไม่ได้กำหนดค่า. |
|  [ValueTask](./valuetask/)(const [TaskPtr](../../system/taskptr/)\&) | สร้าง [ValueTask](./) จาก shared pointer ไปยัง [Task](../task/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IEquatable](../../system/iequatable/)
* เนมสเปส [System::Threading::Tasks](../)
* ไลบรารี [Aspose.Slides](../../)