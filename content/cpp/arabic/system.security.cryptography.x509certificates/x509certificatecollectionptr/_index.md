---
title: X509CertificateCollectionPtr
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مؤشر إلى مجموعة من شهادات X509. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
type: docs
weight: 92
url: /ar/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr فئة

مؤشر إلى مجموعة من شهادات X509. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## طرق

| طريقة | الوصف |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | المستخلص لطريقة [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يُجمع فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | المستخلص لطريقة [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يُجمع فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | المستخلص لطريقة [cbegin()](../../system/smartptr/cbegin/) في مجموعة أساسية. يُجمع فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | المستخلص لطريقة [cend()](../../system/smartptr/cend/) في مجموعة أساسية. يُجمع فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
| auto [end](../../system/smartptr/end/)() | المستخلص لطريقة [end()](../../system/smartptr/end/) في مجموعة أساسية. يُجمع فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | المستخلص لطريقة [end()](../../system/smartptr/end/) في مجموعة أساسية. يُجمع فقط إذا كان SmartPtr_ نوع تخصيص مع طريقة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشار إليه، لكن يتحقق من أن المؤشر في وضعية المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة للكيان المرجعي، بما في ذلك الحالية. يتحقق من أن المؤشر الحالي في وضعية المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | ينادي [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المرجعي الحالي (إن وجد) أو يطرح استثناء. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المرجعي. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشار إليه من نوع معين أو من نوع فرعي له. يتبع دلالات C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق مما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (ينشئ بواسطة مُنشئ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق مما إذا كان المؤشر في وضعية المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق مما إذا كان المؤشر في وضعية الضعيفة. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق مما إذا كان المؤشر غير فارغ. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق مما إذا كان المؤشر فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع إلى الكائن المشار إليه. يتحقق من أن المؤشر غير فارغ. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المرجعي. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر سلوك المقارنة الأقل لفئة [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر سلوك المقارنة الأقل لفئة [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ينقل تعيين كائن [SmartPtr](../../system/smartptr/). يصبح x غير صالح للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ تعيين كائن [SmartPtr](../../system/smartptr/). يجري التحويلات المطلوبة للنوع. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعين مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | يتحقق مما إذا كان المؤشر يشير إلى nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | المستخرج. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل aliasing (الذي تم إنشاؤه بواسطة مُنشئ aliasing) من المؤشر، ويتأكد من أنه يدير (إذا كان مشتركًا) أو يتتبع (إذا كان ضعيفًا) نفس الكائن الذي يشيره إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يضبط الكائن المشار إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط وضع المؤشر. قد يغيّر عدد مرات الإشارة للكيان المرجعي. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينادي طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينتج كائن [SmartPtr](../../system/smartptr/) فارغًا بالوضع المطلوب. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ نسخة من كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين سيشيران إلى نفس الكائن بعد ذلك. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ نسخة من كائن [SmartPtr](../../system/smartptr/). كلا المؤشرين سيشيران إلى نفس الكائن بعد ذلك. ينفّذ تحويل النوع إذا كان مسموحًا. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ينقل إنشاء كائن [SmartPtr](../../system/smartptr/). عمليًا، يبدل المؤشرين إذا كانا من نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحول نوع المصفوفة المرجعية بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان في C# هناك تحويل نوع مصفوفة غير مدعوم في C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يُهيئ مصفوفة فارغة. يُستخدم لترجمة بعض تراكيب كود C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | يبني [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية لـ ptr، لكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحوّل أي نوع مؤشر إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | منشئ مؤشر فارغ. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | منشئ. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، يقلل عداد الإشارة للكائن المشار إليه ويحذف الكائن. |

## راجع أيضًا

* فئة [SmartPtr](../../system/smartptr/)
* نطاق [System::Security::Cryptography::X509Certificates](../)
* مكتبة [Aspose.Slides](../../)