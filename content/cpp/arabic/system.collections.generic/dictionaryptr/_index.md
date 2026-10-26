---
title: DictionaryPtr
second_title: مرجع API لـ Aspose.Slides للغة C++
description: فئة مؤشر القاموس مع تحميل المشغلات. هذا النوع هو مؤشر لإدارة حذف الكائنات الأخرى. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.
type: docs
weight: 170
url: /ar/system.collections.generic/dictionaryptr/
---
## DictionaryPtr فئة


[Dictionary](../dictionary/) فئة مؤشر مع تحميل المشغلات. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```


### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T | نوع المفتاح. |
| V | نوع القيمة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | مُدخل لطريقة [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوع تخصص مع طريقة [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | مُدخل لطريقة [begin()](../../system/smartptr/begin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوع تخصص مع طريقة [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوّل المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوّل المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوّل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | يحوّل المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | مُدخل لطريقة [cbegin()](../../system/smartptr/cbegin/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوع تخصص مع طريقة [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | مُدخل لطريقة [cend()](../../system/smartptr/cend/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوع تخصص مع طريقة [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
|  [DictionaryPtr](./dictionaryptr/)() | يُهيّئ مؤشرًا فارغًا. |
|  [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | يحوّل نوع المؤشر. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
| auto [end](../../system/smartptr/end/)() | مُدخل لطريقة [end()](../../system/smartptr/end/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوع تخصص مع طريقة [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | مُدخل لطريقة [end()](../../system/smartptr/end/) في مجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ نوع تخصص مع طريقة [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | يحصل على نمط المؤشر. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | يحصل على الكائن المشار إليه، لكن يتحقق من أن المؤشر في وضع المشاركة. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة للعنصر المرجعي، بما في ذلك الحالية. يتحقق من أن المؤشر الحالي في وضع المشاركة. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | ينادي [GetHashCode()](../../system/smartptr/gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | يحصل على الكائن المرجعي الحالي (إن وجد) أو يرمي استثناءً. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | يحصل على الكائن المرجعي. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن المشار إليه من نوع محدد أو نوع فرعي له. يتبع سلوك C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | يتحقق إذا كان المؤشر يشير إلى كائن آخر غير المملوك (تم إنشاؤه بواسطة مُنشيء التغيير). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | يتحقق إذا كان المؤشر في وضع المشاركة. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | يتحقق إذا كان المؤشر في وضع الضعف. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | يتحقق إذا كان المؤشر ليس فارغًا. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | يتحقق إذا كان المؤشر فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | يحصل على مرجع إلى الكائن المشار إليه. يتحقق من أن المؤشر ليس فارغًا. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | يسمح بالوصول إلى أعضاء الكائن المرجعي. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | يوفر سلوك المقارنة الأقل للفئة [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | يوفر سلوك المقارنة الأقل للفئة [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ينقل إسناد كائن [SmartPtr](../../system/smartptr/). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ينسخ إسناد كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ينسخ إسناد كائن [SmartPtr](../../system/smartptr/). يقوم بالتحويلات اللازمة للنوع. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | يعين مؤشرًا خامًا إلى كائن [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | يتحقق إذا كان المؤشر يشير إلى nullptr. |
| V\& [operator[]](./operator[]/)(const X\&) const | مشغّل الوصول للعمل مع تحويل نوع المفتاح. |
| V\& [operator[]](./operator[]/)(const T\&) const | مشغّل الوصول. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | يزيل التغيّر (الذي تم إنشاؤه بواسطة مُنشيء التغيير) من المؤشر، ويتأكد من أنه يدير (في حالة المشاركة) أو يتتبع (في حالة الضعف) نفس الكائن الذي يشير إليه. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | يضبط الكائن المشار إليه. |
| void [reset](../../system/smartptr/reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | يضبط نمط المؤشر. قد يغيّر عدد المراجع للكائن المرجعي. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | ينادي طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بالوضع المطلوب. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) مؤشر فارغ بالوضع المطلوب. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بنسخ. كلا المؤشرين سيشيران إلى نفس الكائن بعد ذلك. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بنسخ. كلا المؤشرين سيشيران إلى نفس الكائن بعد ذلك. يقوم بالتحويل إذا كان مسموحًا. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ كائن [SmartPtr](../../system/smartptr/) بنقل. فعليًا، يبدل المؤشرين إذا كانا في نفس الوضع. قد يصبح x غير قابل للاستخدام بعد النداء. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | يحوّل نوع المصفوفة المرجعية بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | يُهيّئ مصفوفة فارغة. يُستخدم لترجمة بعض بنى كود C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ينشئ [SmartPtr](../../system/smartptr/) يشارك معلومات الملكية مع القيمة الأولية للمؤشر ptr، لكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | يحوّل المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | يحوّل أي نوع مؤشر إلى مؤشر إلى [Object](../../system/object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | اختصار للحصول على كائن [System::TypeInfo](../../system/typeinfo/) لنوع Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | يدمر كائن [SmartPtr](../../system/smartptr/). إذا لزم الأمر، يقلل عداد مراجع الكائن المشار إليه ويحذف الكائن. |

## أنظر أيضًا

* فئة [SmartPtr](../../system/smartptr/)
* مساحة الاسم [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)