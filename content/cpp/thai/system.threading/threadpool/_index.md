---
title: ThreadPool
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: API ของ thread pool ที่อนุญาตให้ผลัดงานเข้าสู่คิวเพื่อให้กลุ่มเธรดทำงานอ่านได้ นี้เป็นชนิดแบบสเตติกที่ไม่มีบริการเชิงอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ
type: docs
weight: 222
url: /th/system.threading/threadpool/
---
## คลาส ThreadPool

[Thread](../thread/) API ของ pool ที่อนุญาตให้ผลักดันงานเข้าคิวเพื่อให้กลุ่มเธรดทำงานอ่าน. นี้เป็นชนิดแบบสเตติกที่ไม่มีบริการเชิงอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ.

```cpp
class ThreadPool : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ที่ NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ที่ NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| static void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | รับจำนวนเธรดที่พร้อมใช้งาน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นรุ่นที่คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง |
| static [ThreadPoolImpl](../threadpoolimpl/)\& [GetInstance](./getinstance/)() | อินสแตนซ์การทำงานที่เก็บรายการงานและพารามิเตอร์อื่น ๆ |
| static void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | รับจำนวนเธรดพร้อมกันสูงสุด |
| static void [GetMinThreads](./getminthreads/)(int\&, int\&) | รับจำนวนเธรดต่ำสุดที่ถูกสร้างโดยพูล |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นรุ่นที่คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นรุ่นที่คล้ายกับโอเปอเรเตอร์ C# 'is' |
| static void [JoinAllThreads](./joinallthreads/)() | เข้าร่วมเธรดทั้งหมดที่เป็นของตนเอง. รอโดยไม่มีที่สิ้นสุด |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นรุ่นที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| void [operator=](./operator_equal/)(const [ThreadPool](./)\&) | ไม่มีการคัดลอก |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/)) | ใส่องค์ประกอบงานลงในคิวที่พร้อมกับ callback ที่ไม่มีพารามิเตอร์ |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | ใส่องค์ประกอบงานลงในคิวที่พร้อมกับ callback ที่ไม่มีพารามิเตอร์ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับnullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับที่แชร์ลงตามค่าที่ระบุ |
| static **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | ตั้งค่าจำนวนเธรดที่เป็นของพูล |
| static **bool** [SetMinThreads](./setminthreads/)(int, int) | ตั้งค่าจำนวนเธรดขั้นต่ำที่เป็นของพูล |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
|  [ThreadPool](./threadpool/)(const [ThreadPool](./)\&) | ไม่มีการคัดลอก |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นรุ่นที่คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. คืนหน่วยความจำของโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

```cpp
#include "system/threading/thread_pool.h"
#include "system/threading/thread.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>
#include <mutex>
#include <string>
#include <thread>

const std::string &BooleanToString(bool value)
{
  static const std::string True = "True";
  static const std::string False = "False";

  return value ? True : False;
}

int main()
{
  using namespace System::Threading;
  std::mutex m;

  const auto threadsCount = std::thread::hardware_concurrency();

  for (unsigned int i = 0; i < threadsCount; ++i)
  {
    ThreadPool::QueueUserWorkItem([&m](System::SharedPtr<System::Object> object) -> void {
      auto thread = Thread::get_CurrentThread();
      m.lock();
      std::cout << "Background: " << BooleanToString(thread->get_IsBackground()) <<
        ", Thread pool: " << BooleanToString(thread->get_IsThreadPoolThread()) <<
        ", Thread ID: " << thread->get_ManagedThreadId() << std::endl;
      m.unlock();
    });
  }

  ThreadPool::JoinAllThreads();

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 1
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 3
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 5
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 6
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 9
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 1
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 7
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 2
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 4
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 3
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 12
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 8
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 5
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 6
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 16
พื้นหลัง: True, Thread pool: True, ID ของเธรด: 11
*/
```

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)