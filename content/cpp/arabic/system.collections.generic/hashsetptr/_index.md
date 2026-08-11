---
title: HashSetPtr
second_title: مرجع API لـ Aspose.Slides بلغة C++
description: مؤشر للاحتفاظ بمراجع HashSet. هذا النوع هو مؤشر لإدارة حذف الكائنات الأخرى. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
type: docs
weight: 235
url: /ar/system.collections.generic/hashsetptr/
---
## HashSetPtr فئة

مؤشر للاحتفاظ بمراجع [HashSet](../hashset/). هذا النوع هو مؤشر لإدارة حذف الكائنات الأخرى. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | مستخرج لطريقة [begin()](../../system/smartptr/begin/) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع متخصص مع طريقة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | مستخرج لطريقة [begin()](../../system/smartptr/begin/) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع متخصص مع طريقة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | مستخرج لطريقة [cbegin()](../../system/smartptr/cbegin/) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع متخصص مع طريقة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | مستخرج لطريقة [cend()](../../system/smartptr/cend/) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع متخصص مع طريقة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
| auto [end](../../system/smartptr/end/)() | مستخرج لطريقة [end()](../../system/smartptr/end/) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع متخصص مع طريقة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | مستخرج لطريقة [end()](../../system/smartptr/end/) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع متخصص مع طريقة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشار إليه، لكن يتأكد من أن المؤشر في وضع المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة لكائن الإشارة، بما في ذلك المؤشر الحالي. يتأكد من أن المؤشر الحالي في وضع المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | ينفّذ [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المشار إليه حاليًا (إن وجد) أو يثير استثناء. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المشار إليه. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | منشئ مؤشر فارغ. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | منشئ النسخ. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشار إليه من نوع محدد أو من نوع فرعي له. يتبع دلالة C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق مما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (المُنشأ بواسطة منشئ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق مما إذا كان المؤشر في وضع المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق مما إذا كان المؤشر في وضع الضعيف. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق مما إذا كان المؤشر غير فارغ. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق مما إذا كان المؤشر فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع للكائن المشار إليه. يتأكد من أن المؤشر غير فارغ. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المشار إليه. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر دلالة مقارنة أقل للصف [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر دلالة مقارنة أقل للصف [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ينقل الإسناد إلى كائن [SmartPtr](../../system/smartptr/). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ الإسناد إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ الإسناد إلى كائن [SmartPtr](../../system/smartptr/). يقوم بالتحويلات النوعية المطلوبة. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعين مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | يتحقق مما إذا كان المؤشر يشير إلى nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل aliasing (الذي تم إنشاؤه بواسطة منشئ aliasing) من المؤشر، ويتأكد من أنه يدير (إذا كان مشاركًا) أو يتعقب (إذا كان ضعيفًا) نفس الكائن الذي يشير إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يضبط الكائن المشار إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدد مراجع الكائن المشار إليه. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينفّذ طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) مؤشر فارغ بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ نسخة من كائن [SmartPtr](../../system/smartptr/). بعد ذلك يشير كلا المؤشرين إلى نفس الكائن. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ نسخة من كائن [SmartPtr](../../system/smartptr/). بعد ذلك يشير كلا المؤشرين إلى نفس الكائن. يُجري تحويلًا نوعيًا إذا سُمح به. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالنقل. عمليًا، يبدل مؤشرين إذا كانا في نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحوّل نوع المصفوفة المشار إليها بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يُهيء مصفوفة فارغة. يُستخدم لترجمة بعض بنى كود C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية للـ ptr، لكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحوّل أي نوع من المؤشرات إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، يقلل عداد مراجع الكائن المشار إليه ويحذف الكائن. |

## راجع أيضًا

* فئة [SmartPtr](../../system/smartptr/)
* مساحة الاسم [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)