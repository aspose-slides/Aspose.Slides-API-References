---
title: Monitor
second_title: مرجع API لـ Aspose.Slides للغة C++
description: توفر فئة Monitor آلية تُزامن الوصول إلى الكائنات.
type: docs
weight: 157
url: /ar/system.threading/monitor/
---
## فئة Monitor

فئة [Monitor](./) توفر آلية تُزامن الوصول إلى الكائنات.

```cpp
class Monitor : public System::Object
```

## طرق

| طريقة | الوصف |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يستحوذ على قفل حصري لكائن محدد. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | يستحوذ على قفل حصري للكائن المحدد، ويضبط قيمةً ذريةً تُظهر ما إذا تم أخذ القفل. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام C# [Object.Equals](../../system/object/equals/) دلالات. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يطلق قفلًا حصريًا على الكائن المحدد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثالًا للنوع الموصوف بواسطة targetType. مماثلة لمعامل C# 'is'. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يحدد ما إذا كان الخيط الحالي يحمل القفل على الكائن المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). يُستدعى مباشرة أو يُستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا וيمكّن من إنشاء نسخ من الفئات الفرعية. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يُخطر خيطًا في قائمة الانتظار بتغيير في حالة الكائن المقفل. غير مُنفَّذ. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يُخطر جميع خيوط الانتظار بتغيير في حالة الكائن. غير مُنفَّذ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصّصة إلى سلسلة. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يحاول الحصول على قفل حصري على الكائن المحدد. غير مُنفَّذ. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | يحاول الحصول على قفل حصري على الكائن المحدد، ويضبط قيمةً ذريةً تُظهر ما إذا تم أخذ القفل. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | يحاول، للمدة المحددة بالميليثانية، الحصول على قفل حصري على الكائن المحدد. غير مُنفَّذ. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | يحاول، للمدة المحددة، الحصول على قفل حصري على الكائن المحدد. غير مُنفَّذ. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | يحاول، للمدة المحددة، الحصول على قفل حصري على الكائن المحدد، ويضبط قيمةً ذريةً تُظهر ما إذا تم أخذ القفل. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | يحاول، للمدة المحددة، الحصول على قفل حصري على الكائن المحدد، ويضبط قيمةً ذريةً تُظهر ما إذا تم أخذ القفل. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). يُستدعى مباشرة أو يُستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | يطلق القفل على كائن ويحجز الخيط الحالي حتى يعيد الحصول على القفل. إذا انتهت مدة المهلة المحددة، يدخل الخيط إلى قائمة الانتظار الجاهزة. يمكن أن يخرج من نطاق المزامنة للسياق المتزامن قبل الانتظار ويعيد الدخول بعد ذلك. غير مُنفَّذ. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | يطلق القفل على كائن ويحجز الخيط الحالي حتى يعيد الحصول على القفل. إذا انتهت مدة المهلة المحددة، يدخل الخيط إلى قائمة الانتظار الجاهزة. يمكن أن يخرج من نطاق المزامنة للسياق المتزامن قبل الانتظار ويعيد الدخول بعد ذلك. غير مُنفَّذ. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | يطلق القفل على كائن ويحجز الخيط الحالي حتى يعيد الحصول على القفل. إذا انتهت مدة المهلة المحددة، يدخل الخيط إلى قائمة الانتظار الجاهزة. غير مُنفَّذ. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | يطلق القفل على كائن ويحجز الخيط الحالي حتى يعيد الحصول على القفل. إذا انتهت مدة المهلة المحددة، يدخل الخيط إلى قائمة الانتظار الجاهزة. غير مُنفَّذ. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يطلق القفل على كائن ويحجز الخيط الحالي حتى يعيد الحصول على القفل. غير مُنفَّذ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## ملاحظات

```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
عدد الخيوط: 3
الخيط 0: 1
الخيط 0: 2
الخيط 0: 3
الخيط 0: 4
الخيط 0: 5
الخيط 1: 1
الخيط 1: 2
الخيط 1: 3
الخيط 1: 4
الخيط 1: 5
الخيط 2: 1
الخيط 2: 2
الخيط 2: 3
الخيط 2: 4
الخيط 2: 5
*/
```

## أنظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [System::Threading](../)
* مكتبة [Aspose.Slides](../../)