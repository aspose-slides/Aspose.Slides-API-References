---
title: DynamicWeakPtr
second_title: مرجع API لـ Aspose.Slides للغة C++
description: فئة مؤشر ذكي تتعقب أوضاع المؤشرات لمعلمات القالب للكائن المخزن وتحدّثها بعد كل إسناد. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
type: docs
weight: 781
url: /ar/system/dynamicweakptr/
---
## DynamicWeakPtr الفئة

فئة مؤشر ذكي تتعقب أوضاع المؤشرات للمعاملات القالبية للكائن المخزن وتحديثها بعد كل عملية إسناد. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Pointee | نوع. |
| trunkMode | وضع المؤشر الذكي نفسه، مشترك أو ضعيف. |
| weakLeafs | فهارس معاملات القالب لنوع المخزن التي يجب تعيينها إلى وضع المؤشر الضعيف. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| auto [begin](../smartptr/begin/)() | واجهة للوصول إلى طريقة [begin()](../smartptr/begin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من النوع المتخصص مع طريقة [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | واجهة للوصول إلى طريقة [begin()](../smartptr/begin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من النوع المتخصص مع طريقة [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يحوّل المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يحوّل المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يحوّل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يحوّل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | واجهة للوصول إلى طريقة [cbegin()](../smartptr/cbegin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من النوع المتخصص مع طريقة [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | واجهة للوصول إلى طريقة [cend()](../smartptr/cend/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من النوع المتخصص مع طريقة [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | ينشئ مؤشرًا ذكيًا فارغًا. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | ينشئ مؤشرًا ذكيًا يشير إلى الكائن المعطى. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | يبني نسخة من المؤشر الذكي. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | يبني نسخة من المؤشر الذكي. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | يبني نسخة من المؤشر الذكي. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | يبني المؤشر الذكي بنقل. |
| auto [end](../smartptr/end/)() | واجهة للوصول إلى طريقة [end()](../smartptr/end/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من النوع المتخصص مع طريقة [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | واجهة للوصول إلى طريقة [end()](../smartptr/end/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من النوع المتخصص مع طريقة [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | يحصل على الكائن المشار إليه، لكنه يتأكد من أن المؤشر في وضع مشترك. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة للكيان المشار إليه، بما في ذلك الحالي. يتأكد من أن المؤشر الحالي في وضع مشترك. |
| int [GetHashCode](../smartptr/gethashcode/)() const | يناّد [GetHashCode()](../smartptr/gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | يحصل على الكائن المشار إليه حاليًا (إن وجد) أو يرمي استثناءً. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | يحصل على الكائن المشار إليه. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشار إليه من النوع المحدد أو من نوع طفله. يتبع دلالة C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | يتحقق مما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (تم إنشاؤه بواسطة مُنشئ التسمية المستعارة). |
| **bool** [IsShared](../smartptr/isshared/)() const | يتحقق مما إذا كان المؤشر في وضع مشترك. |
| **bool** [IsWeak](../smartptr/isweak/)() const | يتحقق مما إذا كان المؤشر في وضع ضعيف. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | يتحقق مما إذا كان المؤشر غير فارغ. |
| **bool** [operator!](../smartptr/operator_not/)() const | يتحقق مما إذا كان المؤشر فارغًا. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | يحصل على مرجع للكائن المشار إليه. يتأكد من أن المؤشر غير فارغ. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المشار إليه. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | يوفر دلالة مقارنة أصغر للصف [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | يوفر دلالة مقارنة أصغر للصف [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | ينقل تعيين المؤشر الذكي. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | ينسخ تعيين المؤشر الذكي. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | ينسخ تعيين المؤشر الذكي. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | يعين المؤشر الذكي. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | يضبط المؤشر الذكي إلى فارغ. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يتحقق مما إذا كان المؤشر الذكي فارغًا. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | يزيل التسمية المستعارة (التي تم إنشاؤها بواسطة مُنشئ التسمية المستعارة) من المؤشر، ويتأكد من أنه يدير (إذا كان مشتركًا) أو يتتبع (إذا كان ضعيفًا) نفس الكائن الذي يشيره. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | يضبط الكائن المشار إليه. |
| void [reset](../smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدادات مراجع الكائن المشار إليه. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | يناّد طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | ينشئ كائن [SmartPtr](../smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | ينشئ كائن [SmartPtr](../smartptr/) فارغ بالوضع المطلوب. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ينشئ [SmartPtr](../smartptr/) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | يبني نسخة من كائن [SmartPtr](../smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | يبني نسخة من كائن [SmartPtr](../smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. ينفذ تحويل النوع إذا مسموح. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | يبني كائن [SmartPtr](../smartptr/) بنقل. عمليًا، يبدل مؤشرين إذا كانا في نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | يحوّل نوع المصفوفة المشار إليها بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان في C# هناك تحويل نوع مصفوفة غير مدعوم في C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | يمثل مصفوفة فارغة. يستخدم لترجمة بعض تراكيب كود C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | يبني [SmartPtr](../smartptr/) يشارك معلومات الملكية مع القيمة الأولية للمتغير ptr، لكنه يحمل مؤشرًا غير متعلق وغير مُدار p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | يحوّل أي نوع مؤشر إلى مؤشر إلى [Object](../object/). لا يتطلب اكتمال نوع Pointee_. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../typeinfo/) لنوع Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../smartptr/). إذا لزم الأمر، يقلل عداد مراجع الكائن المشار إليه ويحذف الكائن. |

## التعريفات البديلة

| التعريف البديل | الوصف |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) اسم مستعار للفئة الأساسية. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | اسم مستعار لنوع الذات. |
| [Pointee_](./pointee_/) | نوع المشير. |

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* مساحة الأسماء [System](../)
* المكتبة [Aspose.Slides](../../)