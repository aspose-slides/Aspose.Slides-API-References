---
title: ListPtr
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مؤشر قائمة مع عوامل الوصول. هذا النوع عبارة عن مؤشر لإدارة حذف كائنات أخرى. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
type: docs
weight: 456
url: /ar/system.collections.generic/listptr/
---
## ListPtr فئة

[List](../list/) مؤشر مع عوامل الوصول. هذا النوع هو مؤشر لإدارة حذف كائنات أخرى. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## الطرق

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | المستخرج لـ [begin()](../../system/smartptr/begin/) method من مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوعًا متخصصًا مع طريقة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | المستخرج لـ [begin()](../../system/smartptr/begin/) method من مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوعًا متخصصًا مع طريقة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع الأساس باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | المستخرج لـ [cbegin()](../../system/smartptr/cbegin/) method من مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوعًا متخصصًا مع طريقة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | المستخرج لـ [cend()](../../system/smartptr/cend/) method من مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوعًا متخصصًا مع طريقة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشير إليه. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشير إليه. |
| auto [end](../../system/smartptr/end/)() | المستخرج لـ [end()](../../system/smartptr/end/) method من مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوعًا متخصصًا مع طريقة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | المستخرج لـ [end()](../../system/smartptr/end/) method من مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوعًا متخصصًا مع طريقة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشير إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشير إليه، لكن يفرض أن المؤشر في وضع المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة للكائن المشار إليه، بما فيها الحالي. يفرض أن المؤشر الحالي في وضع المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | ينادي [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشير إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المشار إليه حاليًا (إن وُجد) أو يرمي استثناء. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشير إليه (إن وُجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المشار إليه. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشير إليه (إن وُجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشير إليه من نوع محدد أو نوع طفله. يتبع دلالة 'is' في C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق ما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (مُنشأ بواسطة مُنشيء التماثل). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق ما إذا كان المؤشر في وضع المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق ما إذا كان المؤشر في وضع الضعف. |
|  [ListPtr](./listptr/)(std::nullptr_t) | يهيئ مؤشرًا فارغًا. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | يهيئ المؤشر إلى القائمة المحددة. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق ما إذا كان المؤشر ليس فارغًا. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق ما إذا كان المؤشر فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع إلى الكائن المشير إليه. يفرض أن المؤشر ليس فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يتيح الوصول إلى أعضاء الكائن المشار إليه. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر دلالة مقارنة أصغر لفئة [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر دلالة مقارنة أصغر لفئة [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | يُعيد تعيين كائن [SmartPtr](../../system/smartptr/) بنقل. يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). يقوم بالتحويلات المطلوبة بين الأنواع. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعيّن مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضع قيمة المؤشر إلى nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يتحقق ما إذا كان مؤشر [List](../list/) فارغًا. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | المستخرج. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | المستخرج. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل التماثل (المنشأ بواسطة مُنشيء تماثل) من المؤشر، ويتأكد من أنه يدير (إن كان مشتركًا) أو يتعقّب (إن كان ضعيفًا) نفس الكائن الذي يشيره إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يضبط الكائن المشير إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدد مراجع الكائن المشير إليه. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينادي طريقة SetTemplateWeakPtr() على الكائن المشير إليه (إن وُجد). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن nullptr [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول مؤشرًا خامًا إلى [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | ينسخ بناء كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | ينسخ بناء كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. يقوم بالتحويل بين الأنواع إذا سمح بذلك. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | يبني كائن [SmartPtr](../../system/smartptr/) بنقل. فعليًا، يبدّل مؤشرين إذا كانا من نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحول نوع المصفوفة المشار إليها بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يهيئ مصفوفة فارغة. يُستخدم لترجمة بعض بنى كود C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | يبني [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية لـ ptr، لكنه يحمل مؤشرًا غير مرتبط وغير مدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشير إليه. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحول أي نوع مؤشر إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، يقلل عدد مراجع الكائن المشير إليه ويحذف الكائن. |
## انظر أيضًا

* الفئة [SmartPtr](../../system/smartptr/)
* مساحة الاسم [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)