---
title: QueuePtr
second_title: مرجع API لـ Aspose.Slides للـ C++
description: مؤشر طابور. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
type: docs
weight: 482
url: /ar/system.collections.generic/queueptr/
---
## QueuePtr فئة

[Queue](../queue/) مؤشر. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | الواخذ ل[begin()](../../system/smartptr/begin/) طريقة في مجموعة أساسية. يترجم فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | الواخذ ل[begin()](../../system/smartptr/begin/) طريقة في مجموعة أساسية. يترجم فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | الواخذ ل[cbegin()](../../system/smartptr/cbegin/) طريقة في مجموعة أساسية. يترجم فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | الواخذ ل[cend()](../../system/smartptr/cend/) طريقة في مجموعة أساسية. يترجم فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشير إليه. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشير إليه. |
| auto [end](../../system/smartptr/end/)() | الواخذ ل[end()](../../system/smartptr/end/) طريقة في مجموعة أساسية. يترجم فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | الواخذ ل[end()](../../system/smartptr/end/) طريقة في مجموعة أساسية. يترجم فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشير إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشير إليه، لكن يؤكد أن المؤشر في وضع المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة إلى الكائن المرجعي، بما في ذلك الحالي. يؤكد أن المؤشر الحالي في وضع المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | يستدعي [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشير إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المرجعي الحالي (إن وجد) أو يرمي استثناءً. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشير إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المرجعي. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشير إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن المشير إليه من النوع المحدد أو من نوع فرعي له. يتبع دلالات C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق إذا كان المؤشر يشير إلى كائن آخر غير المملوك (تم إنشاؤه بإنشاء مستعار). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق إذا كان المؤشر في وضع المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق إذا كان المؤشر في وضع الضعيف. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق إذا كان المؤشر غير فارغ. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق إذا كان المؤشر فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع إلى الكائن المشير إليه. يؤكد أن المؤشر غير فارغ. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المرجعي. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر دلالات المقارنة الأقل لـ[SmartPtr](../../system/smartptr/) الفئة. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر دلالات المقارنة الأقل لـ[SmartPtr](../../system/smartptr/) الفئة. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ينقل تعيين كائن [SmartPtr](../../system/smartptr/). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). يقوم بالتحويلات اللازمة للأنواع. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعيّن مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | يتحقق إذا كان المؤشر يشير إلى nullptr. |
|  [QueuePtr](./queueptr/)() | ينشئ مؤشرًا فارغًا. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | ينشئ مؤشرًا إلى طابور محدد. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل الاستعارة (المنتجة بإنشاء مستعار) من المؤشر، ويتأكد من أنه يدير (إذا كان مشتركًا) أو يتتبع (إذا كان ضعيفًا) نفس الكائن الذي يشير إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يعيّن الكائن المشير إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدادات الإشارة للكائن المرجعي. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | يستدعي طريقة SetTemplateWeakPtr() على الكائن المشير إليه (إن وجد). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) مؤشر فارغ بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول مؤشرًا خامًا إلى [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | ينسخ بناء كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | ينسخ بناء كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. ينفّذ تحويل النوع إذا سُمح بذلك. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ينقل بناء كائن [SmartPtr](../../system/smartptr/). فعليًا، يبدل مؤشرين إذا كانا من نفس الوضع. قد يصبح x غير قابل للاستخدام بعد النداء. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحوّل نوع المصفوفة المرجعية بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يهيّء مصفوفة فارغة. يُستخدم لتحويل بعض تراكيب الكود في C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | يبني [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية للمؤشر، لكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشير إليه. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحوّل أي نوع مؤشر إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ كاملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، يقلل عداد مرجع الكائن المشير إليه ويحذف الكائن. |

## انظر أيضًا

* فئة [SmartPtr](../../system/smartptr/)
* مساحة الاسم [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)