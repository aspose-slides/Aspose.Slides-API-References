---
title: IMathArrayFactory
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسمح بإنشاء مصفوفة رياضية
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imatharrayfactory/
---
## فئة IMathArrayFactory

يسمح بإنشاء مصفوفة رياضية

```cpp
class IMathArrayFactory : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [CreateMathArray](./creatematharray/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [CreateMathArray](./creatematharray/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElementCollection](../imathelementcollection/)\>) | ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNs متساوية على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNs متساوية على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. يتيح تجزئة الكائنات المخصصة |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء [System.Object.GetType()](../../system/object/gettype/) في C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. نظير عامل 'is' في C# |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير lock() في C#. استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصصة |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع الهياكل الداخلية |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالبي الـ n'th ليكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة [Object.ToString()](../../system/object/tostring/) في C#. يتيح تحويل الكائنات المخصصة إلى سلسلة |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء typeof([System.Object](../../system/object/)) في C# |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير lock() في C#. استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع الهياكل الداخلية |

## ملاحظات

للتوافق مع COM 

## انظر أيضًا

* الفئة [Object](../../system/object/)
* نطاق الاسم [Aspose::Slides::MathText](../)
* المكتبة [Aspose.Slides](../../)