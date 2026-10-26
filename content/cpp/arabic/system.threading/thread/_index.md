---
title: Thread
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تنفيذ الخيط. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تنشئ مثيلاً لهذا النوع على المكدس أو باستخدام المشغّل new، لأنه سيسبب أخطاء زمن تشغيل و/أو أعطال تأكيد. دائمًا ضع هذه الفئة داخل مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 209
url: /ar/system.threading/thread/
---
## فئة Thread

[Thread](./) تنفيذ. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيسبب أخطاء زمن تشغيل و/أو أخطاء تأكيد. دائمًا ضع هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
class Thread : public System::Object
```

## طرق

| طريقة | الوصف |
| --- | --- |
| void [Abort](./abort/)() | يُوقف الخيط. غير مُنفذ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعْتَبَر NaNانين متساويتين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعْتَبَر NaNانين متساويتين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | يحصل على ثقافة الخيط. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | يحصل على كائن يصف الخيط الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | يحصل على ثقافة واجهة المستخدم المستخدمة بواسطة الخيط. |
| **bool** [get_IsAlive](./get_isalive/)() | يتحقق مما إذا كان الخيط ما زال حيا. |
| **bool** [get_IsBackground](./get_isbackground/)() | يتحقق مما إذا كان الخيط في الخلفية. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | يتحقق مما إذا كان الخيط مملوكًا من قبل مجموعة خيوط. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | يحصل على معرّف الخيط. يمكن الحصول عليه من نظام التشغيل، ولكن إذا تجاوز معرف خيط نظام التشغيل حدود int، قد تتقاطع معرّفات الخيوط. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | يحصل على اسم الخيط. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | يحصل على حالة الخيط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | يحصل على معرّف الخيط الحالي. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Interrupt](./interrupt/)() | يقاطع الخيط. غير مُنفذ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا لنوع موصوف بواسطة targetType. نظير مشغل C# 'is'. |
| void [Join](./join/)() | ينضم إلى الخيط المُدار. يُجري انتظارًا غير محدود إذا لزم الأمر. |
| **bool** [Join](./join/)(int) | ينضم إلى الخيط المُدار. يُجري انتظارًا محدودًا. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | ينضم إلى الخيط المُدار. يُجري انتظارًا محدودًا. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| static void [MemoryBarrier](./memorybarrier/)() | يُزامن وصول الذاكرة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويسمح بإنشاء النسخ من الفئات الفرعية. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | ينُسخ بيانات TLS من خيط مختلف. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويسمح بإنشاء النسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجعية لكائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يضبط ثقافة الخيط. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يضبط ثقافة واجهة المستخدم المستخدمة من قبل الخيط. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | يضبط الخيط كخلفية أو أمامية. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | يضبط اسم الخيط. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط الن المعيّن لقالب على مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| static void [Sleep](./sleep/)(int) | يوقف الخيط الحالي لمدة زمنية محددة. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | يوقف الخيط الحالي لمدة زمنية محددة. |
| static void [SpinWait](./spinwait/)(int) | ينتظر عددًا محددًا من دورات الحلقة. |
| void [Start](./start/)() | يبدأ الخيط باستخدام كائن حجة فارغ. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يبدأ الخيط. |
|  [Thread](./thread/)() | منشئ. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | منشئ. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | منشئ. |
|  [Thread](./thread/)([Thread](./)\&) | منشئ نسخة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| static **bool** [Yield](./yield/)() | يعطي صلاحية الخيط. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحذف جميع هياكل البيانات الداخلية. |
| virtual  [~Thread](./~thread/)() | مُدمر. |

## ملاحظات

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
هذا المثال البرمجي ينتج الإخراج التالي:
معرّف الخيط الرئيسي: 2
معرّف الخيط الفرعي: 1
*/
```

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Threading](../)
* المكتبة [Aspose.Slides](../../)