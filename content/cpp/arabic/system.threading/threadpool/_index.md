---
title: ThreadPool
second_title: مرجع API لـ Aspose.Slides للغة C++
description: واجهة برمجة تطبيقات تجمع الخيوط التي تسمح بدفع الوظائف إلى الطابور لتتم قراءتها من قبل مجموعة من خيوط العمل. هذا نوع ثابت لا يوفر خدمات كائنات. يجب ألا تقوم بإنشاء أي نسخ منه بأي وسيلة.
type: docs
weight: 222
url: /ar/system.threading/threadpool/
---
## ThreadPool فئة


[Thread](../thread/) واجهة برمجة تطبيقات التجمع تسمح بدفع الوظائف إلى الطابور ليتم قراءتها من قبل مجموعة من خيوط العمل. هذا نوع ثابت لا يوفر خدمات كائنات. يجب ألا تقوم بإنشاء أي نسخ منه بأي طريقة.

```cpp
class ThreadPool : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقوم بمقارنة الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقوم بمقارنة كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقوم بمقارنة كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | يُحصل على عدد خيوط التنفيذ المتاحة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يُحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| static [ThreadPoolImpl](../threadpoolimpl/)\& [GetInstance](./getinstance/)() | مثيل التنفيذ الذي يحتفظ بقائمة الوظائف ومعلمات أخرى. |
| static void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | يُحصل على الحد الأقصى لعدد الخيوط المتزامنة. |
| static void [GetMinThreads](./getminthreads/)(int\&, int\&) | يُحصل على الحد الأدنى لعدد الخيوط التي يُنشئها التجمع. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يُحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الوصوف بـ targetType. مماثل لمعامل C# 'is'. |
| static void [JoinAllThreads](./joinallthreads/)() | ينضم إلى جميع الخيوط المملوكة. ينتظر إلى ما لا نهاية. |
| void [Lock](../../system/object/lock/)() | يطبق بيان القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| void [operator=](./operator_equal/)(const [ThreadPool](./)\&) | بدون نسخ. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/)) | يضع عنصر عمل في الطابور مع وجود رد اتصال بدون معلمات. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يضع عنصر عمل في الطابور مع وجود رد اتصال بدون معلمات. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقوم بمقارنة الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقوم بمقارنة الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| static **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | يضبط عدد الخيوط المملوكة للتجمع. |
| static **bool** [SetMinThreads](./setminthreads/)(int, int) | يضبط الحد الأدنى لعدد الخيوط المملوكة للتجمع. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n'th ليكون مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يُحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بتقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [ThreadPool](./threadpool/)(const [ThreadPool](./)\&) | بدون نسخ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق بيان إلغاء القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بتقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## ملاحظات



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
مثال الشيفرة هذا ينتج المخرجات التالية:
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 1
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 3
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 5
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 6
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 9
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 1
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 7
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 2
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 4
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 3
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 12
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 8
الخلفية: True, مجمع الخيط: True, معرف الخيط: 5
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 6
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 16
الخلفية: True, مجمع الخيوط: True, معرف الخيط: 11
*/
```

## أنظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Threading](../)
* المكتبة [Aspose.Slides](../../)