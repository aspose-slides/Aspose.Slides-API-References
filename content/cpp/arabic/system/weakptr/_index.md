---
title: WeakPtr
second_title: مرجع API Aspose.Slides للغة C++
description: "فئة فرعية من System::SmartPtr تقوم بضبط نفسها على وضعية الضعف عند الإنشاء. يرجى ملاحظة أن هذه الفئة لا تضمن أن مثيلها سيظل دائمًا في وضعية الضعف لأن set_Mode() لا يزال قابلًا للوصول. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت."
type: docs
weight: 1496
url: /ar/system/weakptr/
---
## فئة WeakPtr

فئة فرعية من [System::SmartPtr](../smartptr/) تقوم بضبط نفسها على وضعية الضعف عند الإنشاء. يرجى ملاحظة أن هذه الفئة لا تضمن أن مثيلها سيظل دائمًا في وضعية الضعف لأن [set_Mode()](../smartptr/set_mode/) لا يزال قابلًا للوصول. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المؤشر. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| auto [begin](../smartptr/begin/)() | المستخلص للوصول إلى طريقة [begin()](../smartptr/begin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصص يحتوي على طريقة [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | المستخلص للوصول إلى طريقة [begin()](../smartptr/begin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصص يحتوي على طريقة [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يقوم بتحويل المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | المستخلص للوصول إلى طريقة [cbegin()](../smartptr/cbegin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصص يحتوي على طريقة [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | المستخلص للوصول إلى طريقة [cend()](../smartptr/cend/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصص يحتوي على طريقة [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشير إليه. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشير إليه. |
| auto [end](../smartptr/end/)() | المستخلص للوصول إلى طريقة [end()](../smartptr/end/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصص يحتوي على طريقة [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | المستخلص للوصول إلى طريقة [end()](../smartptr/end/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصص يحتوي على طريقة [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | يتحقق مما إذا كان الكائن المشار إليه قد تم حذفه بالفعل. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | يعيد الكائن المشير إليه. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | يعيد وضع المؤشر. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | يعيد الكائن المشير إليه، ولكنه يتحقق من أن المؤشر في وضعية مشاركة. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | يعيد عدد مؤشرات المشاركة الموجودة للكائن المشار إليه، بما في ذلك المؤشر الحالي. يتحقق من أن المؤشر الحالي في وضعية مشاركة. |
| [Object](../object/) * [get_weak](./get_weak/)() const | يعيد الكائن المشار إليه. يتحقق من أن المؤشر في وضعية ضعف. |
| int [GetHashCode](../smartptr/gethashcode/)() const | ينادي [GetHashCode()](../smartptr/gethashcode/) على الكائن المشير إليه. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | يعيد الكائن المشار إليه حاليًا (إن وجد) أو يرمي استثناءً. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | يعيد الكائن المشير إليه (إن وجد) أو nullptr. نفس [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | يعيد الكائن المشار إليه. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | يعيد الكائن المشير إليه (إن وجد) أو nullptr. نفس [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشير إليه من نوع محدد أو من نوع فرعي له. يتبع semantics 'is' في C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | يتحقق مما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (تم إنشاؤه بواسطة مُنشئ التسمية المستعارة). |
| **bool** [IsShared](../smartptr/isshared/)() const | يتحقق مما إذا كان المؤشر في وضعية مشاركة. |
| **bool** [IsWeak](../smartptr/isweak/)() const | يتحقق مما إذا كان المؤشر في وضعية ضعف. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | يتحقق مما إذا كان المؤشر ليس null. |
| **bool** [operator!](../smartptr/operator_not/)() const | يتحقق مما إذا كان المؤشر null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | يعيد مرجعًا إلى الكائن المشير إليه. يتحقق من أن المؤشر ليس null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المشار إليه. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | يوفر semantics مقارنة أصغر لفئة [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | يوفر semantics مقارنة أصغر لفئة [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | يعين قيمة للمؤشر الضعيف. يستدعي مشغل الإسناد المحدد لـ SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | ينفذ إسنادًا حركيًا لكائن [SmartPtr](../smartptr/). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | ينفذ إسنادًا نسخيًا لكائن [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | ينفذ إسنادًا نسخيًا لكائن [SmartPtr](../smartptr/). يقوم بالتحويلات النوعية المطلوبة. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | يعين مؤشرًا خامًا إلى كائن [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يتحقق مما إذا كان المؤشر الضعيف null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | يزيل التسمية المستعارة (التي تم إنشاؤها بواسطة مُنشئ التسمية المستعارة) من المؤشر، ويتأكد من أنه يدير (إذا كان مشتركًا) أو يتتبع (إذا كان ضعيفًا) نفس الكائن الذي يشير إليه. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | يضبط الكائن المشير إليه. |
| void [reset](../smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدد مراجع الكائن المشار إليه. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينادي طريقة SetTemplateWeakPtr() على الكائن المشير إليه (إن وجد). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | إنشاء كائن [SmartPtr](../smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | إنشاء كائن [SmartPtr](../smartptr/) مؤشره null بالوضع المطلوب. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | إنشاء [SmartPtr](../smartptr/) يشير إلى الكائن المحدد، أو تحويل المؤشر الخام إلى [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | إنشاء نسخة نسخية لكائن [SmartPtr](../smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | إنشاء نسخة نسخية لكائن [SmartPtr](../smartptr/). كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. ينفذ تحويل النوع إذا كان مسموحًا. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | إنشاء نسخة حركية لكائن [SmartPtr](../smartptr/). فعليًا، يتم تبادل المؤشرين إذا كانا من نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | يقوم بتحويل نوع المصفوفة المشار إليها بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | يُهيئ مصفوفة فارغة. يُستخدم لترجمة بعض تراكيب كود C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ينشئ [SmartPtr](../smartptr/) يشارك معلومات الملكية مع القيمة الأولية لـ ptr، ولكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشير إليه. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | يقوم بتحويل أي نوع مؤشر إلى مؤشر إلى [Object](../object/). لا يتطلب أن يكون نوع Pointee_ كاملاً. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../typeinfo/) لنوع Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | ينشئ مؤشرًا null. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | ينشئ مؤشرًا ضعيفًا للكائن المعطى. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | ينشئ مؤشرًا ضعيفًا يشير إلى نفس المؤشر الذي يشير إليه ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | ينشئ مؤشرًا ضعيفًا يشير إلى نفس المؤشر الذي يشير إليه x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | ينشئ نسخة نسخية لمؤشر ضعيف. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | ينشئ نسخة نسخية لمؤشر ضعيف. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | ينشئ نسخة حركية لمؤشر ضعيف. |
|  [~SmartPtr](../smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../smartptr/). إذا لزم الأمر، يقلل عداد مرجع الكائن المشير إليه ويحذف الكائن. |

## التعريفات النوعية

| التعريف | الوصف |
| --- | --- |
| [SmartPtr_](./smartptr_/) | اسم مستعار للفئة [SmartPtr](../smartptr/) المقابلة. |
| [WeakPtr_](./weakptr_/) | اسم مستعار لنوع الذات. |
| [Pointee_](./pointee_/) | نوع المؤشر. |

## انظر أيضًا

* فئة [SmartPtr](../smartptr/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)