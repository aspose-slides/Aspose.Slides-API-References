---
title: StringCollectionPtr
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مجموعة سلاسل مؤشر مع عامل الوصول.
type: docs
weight: 40
url: /ar/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr فئة

مجموعة سلاسل مؤشر مع عامل الوصول.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```
## Methods

| الطريقة | الوصف |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | المُستدخِل لطريقة [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يُجَمِّد فقط إذا كان SmartPtr_ من نوع تخصصي يحتوي على طريقة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | المُستدخِل لطريقة [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يُجَمِّد فقط إذا كان SmartPtr_ من نوع تخصصي يحتوي على طريقة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوِّل المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوِّل المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوِّل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوِّل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | المُستدخِل لطريقة [cbegin()](../../system/smartptr/cbegin/) في مجموعة أساسية. يُجَمِّد فقط إذا كان SmartPtr_ من نوع تخصصي يحتوي على طريقة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | المُستدخِل لطريقة [cend()](../../system/smartptr/cend/) في مجموعة أساسية. يُجَمِّد فقط إذا كان SmartPtr_ من نوع تخصصي يحتوي على طريقة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يحوِّل المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يحوِّل المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
| auto [end](../../system/smartptr/end/)() | المُستدخِل لطريقة [end()](../../system/smartptr/end/) في مجموعة أساسية. يُجَمِّد فقط إذا كان SmartPtr_ من نوع تخصصي يحتوي على طريقة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | المُستدخِل لطريقة [end()](../../system/smartptr/end/) في مجموعة أساسية. يُجَمِّد فقط إذا كان SmartPtr_ من نوع تخصصي يحتوي على طريقة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشار إليه، لكن يفرض أن المؤشر في وضعية المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد مؤشرات المشاركة الموجودة إلى الكائن المرجعي، بما في ذلك الحالي. يفرض أن المؤشر الحالي في وضعية المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | ينادى [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المرجعي الحالي (إن وجد) أو يرمي استثناء. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المرجعي. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن المشار إليه من نوع معين أو من أحد الأنواع الفرعية له. يتبع دلالة C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق ما إذا كان المؤشر يشير إلى كائن غير المملوك (تم إنشاؤه بواسطة مُنشيء التسمية المستعارة). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق ما إذا كان المؤشر في وضعية المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق ما إذا كان المؤشر في وضعية الضعيفة. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق ما إذا كان المؤشر غير فارغ. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق ما إذا كان المؤشر فارغ. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع للكائن المشار إليه. يفرض أن المؤشر غير فارغ. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المرجعي. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر دلالة المقارنة الأقل للصف [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر دلالة المقارنة الأقل للصف [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ينقل تعيين كائن [SmartPtr](../../system/smartptr/). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). يقوم بتحويل الأنواع المطلوبة. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعين مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | يتحقق ما إذا كان المؤشر يشير إلى nullptr. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | دالة مستدخِل. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل التسمية المستعارة (التي تم إنشاؤها بواسطة مُنشيء التسمية المستعارة) من المؤشر، ويتأكد أنه يدير (إذا كان مشاركة) أو يتعقب (إذا كان ضعيف) نفس الكائن الذي يشير إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يضبط الكائن المشار إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدد مراجع الكائن المرجعي. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينادى طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) مؤشر فارغ بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ نسخة نسخة من كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ نسخة نسخة من كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. يجري تحويل النوع إذا مسموح. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ بنقل كائن [SmartPtr](../../system/smartptr/). عمليًا، يبدل المؤشرين إذا كانا في نفس الوضعية. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحوِّل نوع المصفوفة المرجعية بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان في C# هناك تحويل نوع مصفوفة غير مدعوم في C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يُهيئ مصفوفة فارغة. يستخدم لترجمة بعض بنى كود C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية للمتغيّر ptr، لكنه يحمل مؤشر غير مرتبط وغير مُدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يحوِّل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
|  [StringCollectionPtr](./stringcollectionptr/)() | ينشئ مؤشرًا فارغًا. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | ينشئ مؤشرًا إلى مجموعة محددة. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحوِّل أي نوع مؤشر إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، يقلل عداد مراجع الكائن المشار إليه ويحذف الكائن. |
## انظر أيضًا

* فئة [SmartPtr](../../system/smartptr/)
* مساحة الاسم [System::Collections::Specialized](../)
* مكتبة [Aspose.Slides](../../)