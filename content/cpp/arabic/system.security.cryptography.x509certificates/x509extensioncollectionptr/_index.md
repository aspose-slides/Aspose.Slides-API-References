---
title: X509ExtensionCollectionPtr
second_title: مرجع API Aspose.Slides للغة C++
description: مؤشر إلى مجموعة من امتدادات X509. هذا النوع هو مؤشر لإدارة حذف الكائن الآخر. ينبغي تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالإشارة الثابتة.
type: docs
weight: 170
url: /ar/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr فئة


مؤشر إلى مجموعة من امتدادات X509. هذا النوع هو مؤشر لإدارة حذف الكائن الآخر. يجب تخصيصه على مكدس وتمريره إلى الدوال إما بالقيمة أو بالإشارة الثابتة.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دالة وصول لـ [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يتم تجميعها فقط إذا كان SmartPtr_ نوعًا متخصصًا مع دالة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | دالة وصول لـ [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يتم تجميعها فقط إذا كان SmartPtr_ نوعًا متخصصًا مع دالة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يقوم بتحويل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دالة وصول لـ [cbegin()](../../system/smartptr/cbegin/) في مجموعة أساسية. يتم تجميعها فقط إذا كان SmartPtr_ نوعًا متخصصًا مع دالة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | دالة وصول لـ [cend()](../../system/smartptr/cend/) في مجموعة أساسية. يتم تجميعها فقط إذا كان SmartPtr_ نوعًا متخصصًا مع دالة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
| auto [end](../../system/smartptr/end/)() | دالة وصول لـ [end()](../../system/smartptr/end/) في مجموعة أساسية. يتم تجميعها فقط إذا كان SmartPtr_ نوعًا متخصصًا مع دالة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | دالة وصول لـ [end()](../../system/smartptr/end/) في مجموعة أساسية. يتم تجميعها فقط إذا كان SmartPtr_ نوعًا متخصصًا مع دالة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشار إليه، لكن يؤكد أن المؤشر في وضع المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة للكيان المشار إليه، بما في ذلك الحالي. يؤكد أن المؤشر الحالي في وضع المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | ينفّذ [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المشار إليه حاليًا (إن وجد) أو يرمي استثناء. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المشار إليه. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشار إليه من نوع محدد أو من نوع طفله. يتبع دلالات 'is' في C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق مما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (منشئ الإشارة المستعارة). |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق مما إذا كان المؤشر في وضع المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق مما إذا كان المؤشر في وضع الضعيف. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق مما إذا كان المؤشر ليس صفراً. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق مما إذا كان المؤشر صفراً. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع إلى الكائن المشار إليه. يؤكد أن المؤشر ليس صفراً. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يتيح الوصول إلى أعضاء الكائن المشار إليه. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر دلالة مقارنة 'أقل' للفئة [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر دلالة مقارنة 'أقل' للفئة [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ينقل تعيين كائن [SmartPtr](../../system/smartptr/). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). يقوم بالتحويلات المطلوبة للنوع. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعين مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | يتحقق مما إذا كان المؤشر يشير إلى nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | دالة وصول. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل الإشارة المستعارة (المنشأة بواسطة منشئ الإشارة المستعارة) من المؤشر، ويتأكد من أنه يدير (إذا كان مشاركًا) أو يتعقب (إذا كان ضعيفًا) نفس الكائن الذي يشير إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يضبط الكائن المشار إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدد مراجع الكائن المشار إليه. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينفّذ طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) ذات مؤشر فارغ بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول مؤشرًا خامًا إلى [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | يقوم بإنشاء نسخة من كائن [SmartPtr](../../system/smartptr/). يشير كلا المؤشرين إلى نفس الكائن لاحقًا. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يقوم بإنشاء نسخة من كائن [SmartPtr](../../system/smartptr/). يشير كلا المؤشرين إلى نفس الكائن لاحقًا. ينفّذ تحويل النوع إذا مسموح. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) عن طريق النقل. فعليًا، يبادل المؤشرين إذا كانا في نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحوّل نوع المصفوفة المشار إليها بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يُهيئ مصفوفة فارغة. يُستخدم لترجمة بعض بنى كود C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية للـ ptr، لكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يقوم بتحويل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحوّل أي نوع مؤشر إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | منشئ مؤشر فارغ. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | منشئ. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، ينقص عداد مرجع الكائن المشار إليه ويحذف الكائن. |
## انظر أيضًا

* الفئة [SmartPtr](../../system/smartptr/)
* مساحة الاسم [System::Security::Cryptography::X509Certificates](../)
* المكتبة [Aspose.Slides](../../)