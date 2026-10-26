---
title: Thread
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: "การทำงานของ Thread. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ในพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 209
url: /th/system.threading/thread/
---
## Thread คลาส


[Thread](./) การดำเนินการ. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ในตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class Thread : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Abort](./abort/)() | ยกเลิกเธรด. ยังไม่ถูกใช้งาน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ตามสไตล์ของ C# ซึ่ง NaN สองค่าเหล่านี้จะถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ตามสไตล์ของ C# ซึ่ง NaN สองค่าเหล่านี้จะถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับใช้ภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | รับค่า culture ของเธรด. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | รับอ็อบเจกต์ที่อธิบายเธรดปัจจุบัน. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | รับ culture ของอินเทอร์เฟซผู้ใช้ที่ใช้โดยเธรด. |
| **bool** [get_IsAlive](./get_isalive/)() | ตรวจสอบว่าเธรดยังทำงานอยู่หรือไม่. |
| **bool** [get_IsBackground](./get_isbackground/)() | ตรวจสอบว่าเธรดเป็นพื้นหลังหรือไม่. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | ตรวจสอบว่าเธรดเป็นของ thread pool หรือไม่. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | รับตัวระบุของเธรด. สามารถดึงได้จาก OS แต่หากตัวระบุเธรดของ OS เกินขอบเขตของ int, ID ของเธรดอาจทับซ้อนกัน. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | รับชื่อของเธรด. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | รับสถานะของเธรด. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจกต์. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | รับตัวระบุของเธรดปัจจุบัน. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Interrupt](./interrupt/)() | ขัดจังหวะเธรด. ยังไม่ถูกใช้งาน. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบาย. คล้าย operator 'is' ของ C#. |
| void [Join](./join/)() | เข้าร่วมเธรดที่จัดการ. ทำการรอโดยไม่จำกัดหากจำเป็น. |
| **bool** [Join](./join/)(int) | เข้าร่วมเธรดที่จัดการ. ทำการรอแบบจำกัด. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | เข้าร่วมเธรดที่จัดการ. ทำการรอแบบจำกัด. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
| static void [MemoryBarrier](./memorybarrier/)() | ทำการซิงโครไนซ์การเข้าถึงหน่วยความจำ. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | คัดลอกข้อมูล TLS จากเธรดที่แตกต่าง. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์แบบค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | ตั้งค่า culture ของเธรด. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | ตั้งค่า culture ของอินเทอร์เฟซผู้ใช้ที่ใช้โดยเธรด. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | ตั้งค่าให้เธรดเป็นพื้นหลังหรือพื้นหน้า. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | ตั้งชื่อเธรด. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| static void [Sleep](./sleep/)(int) | หยุดเธรดปัจจุบันเป็นเวลาที่กำหนด. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | หยุดเธรดปัจจุบันเป็นเวลาที่กำหนด. |
| static void [SpinWait](./spinwait/)(int) | รอจนกว่าจะครบจำนวนรอบลูปที่กำหนด. |
| void [Start](./start/)() | เริ่มเธรดโดยใช้อ็อบเจกต์อาร์กิวเมนต์ null. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | เริ่มเธรด. |
|  [Thread](./thread/)() | คอนสตรัคเตอร์. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | คอนสตรัคเตอร์. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | คอนสตรัคเตอร์. |
|  [Thread](./thread/)([Thread](./)\&) | คอนสตรัคเตอร์คัดลอก. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| static **bool** [Yield](./yield/)() | ให้เธรด yield. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
| virtual  [~Thread](./~thread/)() | ดีสตรักเตอร์. |
## หมายเหตุ



```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
โค้ดตัวอย่างนี้สร้างผลลัพธ์ต่อไปนี้:
Main thread ID: 2
Child thread ID: 1
*/
```

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)