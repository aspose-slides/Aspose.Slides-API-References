---
title: SmartPtr
second_title: "مرجع API لـ Aspose.Slides للـ C++"
description: "فئة مؤشر لتغليف الأنواع التي يتم تخصيصها على الذاكرة الديناميكية. استخدمها لإدارة الذاكرة للفئات التي ترث Object. يتبع هذا النوع من المؤشرات سلوك المؤشرات المتداخلة. يُخزن عداد المرجعية إما في Object نفسها أو في بنية العداد المرتبطة بكيان Object بشكل وثيق. على أي حال، جميع مثيلات SmartPtr تشكل مجموعة ملكية واحدة بغض النظر عن طريقة إنشائها، وهذا يختلف عن سلوك فئة std::shared_ptr. تحويل مؤشر خام إلى SmartPtr آمن طالما توجد مثيلات SmartPtr أخرى تحتفظ بمراجع مشتركة إلى نفس الكائن. يمكن أن تكون نسخة فئة SmartPtr في إحدى حالتين: مؤشر مشترك ومؤشر ضعيف. للحفاظ على بقاء الكائن حيًا، يجب أن يكون عدد المراجع المشتركة إليه إيجابيًا. يمكن استخدام المؤشرات الضعيفة والمشتركة للوصول إلى الكائن المشار إليه (لاستدعاء الطرق، قراءة أو كتابة الحقول، إلخ)، لكن المؤشرات الضعيفة لا تشارك في عدّ مراجع المؤشرات المشتركة. يتم حذف Object عندما يتم تدمير آخر مؤشر 'shared' SmartPtr يشيره. لذلك، تأكد من عدم حدوث ذلك عندما لا توجد مؤشرات SmartPtr مشتركة أخرى إلى الكائن، مثل أثناء إنشاء الكائن أو تدميره. استخدم كائنات الحراسة System::Object::ThisProtector (في كود C++) أو السمتين CppCTORSelfReference أو CppSelfReference (في كود C# المُترجم) لإصلاح هذه المشكلة. بالمثل، تأكد من كسر الإشارات الدائرية باستخدام فئة المؤشر System::WeakPtr أو وضع المؤشر System::SmartPtrMode::Weak (في كود C++) أو سمة CppWeakPtr (في كود C# المُترجم). إذا كان هناك كائنين أو أكثر يشيران إلى بعضهما باستخدام مؤشرات 'shared'، فإنهما لن يتم حذفهما أبدًا. إذا كان يجب تغيير نوع المؤشر (ضعيف أو مشترك) أثناء التشغيل، استخدم الطريقة System::SmartPtr<T>::set_Mode() أو الفئة System::DynamicWeakPtr. لا تحتوي فئة SmartPtr على أي طرق افتراضية. يجب أن ترثها فقط إذا كنت تنشئ استراتيجية إدارة ذاكرة خاصة بك. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت."
type: docs
weight: 1236
url: /ar/system/smartptr/
---
## فئة SmartPtr

فئة المؤشر لتغليف الأنواع التي تُخصص على الذاكرة الديناميكية. استخدمها لإدارة الذاكرة للفئات التي ترث [Object](../object/). يتبع هذا النوع من المؤشرات سلوك المؤشرات المتداخلة. يتم تخزين عداد المرجعية إما في [Object](../object/) نفسها أو في بنية العداد المرتبطة بصورة وثيقة بكيان [Object](../object/). على أي حال، جميع كائنات [SmartPtr](./) تشكل مجموعة ملكية واحدة بغض النظر عن طريقة إنشائها، وهو ما يختلف عن سلوك فئة std::shared_ptr. تحويل المؤشر الخام إلى [SmartPtr](./) آمن طالما توجد كائنات [SmartPtr](./) أخرى تحتفظ بمراجع مشتركة إلى نفس الكائن. يمكن أن تكون نسخة فئة [SmartPtr](./) في إحدى حالتين: مؤشر مشترك ومؤشر ضعيف. للحفاظ على بقاء الكائن حيًا، يجب أن يكون عدد المراجع المشتركة له إيجابيًا. يمكن استخدام كلا من المؤشرات الضعيفة والمشتركة للوصول إلى الكائن المشار إليه (لاستدعاء الطرق، قراءة أو كتابة الحقول، إلخ)، لكن المؤشرات الضعيفة لا تشارك في عدّ المراجع للمؤشرات المشتركة. يتم حذف [Object](../object/) عندما يتم تدمير آخر مؤشر 'shared' [SmartPtr](./) يشير إليه. لذا، تأكد من عدم حدوث ذلك عندما لا توجد مؤشرات مشتركة [SmartPtr](./) أخرى إلى الكائن، مثال ذلك أثناء إنشاء الكائن أو تدميره. استخدم كائنات الحراسة System::Object::ThisProtector (في كود C++) أو السمتين CppCTORSelfReference أو CppSelfReference (في كود C# المترجم) لإصلاح هذه المشكلة. بالمثل، تأكد من كسر الإشارات الدائرية باستخدام فئة المؤشر [System::WeakPtr](../weakptr/) أو وضع المؤشر [System::SmartPtrMode::Weak](../smartptrmode/) (في كود C++) أو السمة CppWeakPtr (في كود C# المترجم). إذا كان هناك كائنان أو أكثر يشيران إلى بعضهما باستخدام مؤشرات 'shared'، فلن يتم حذفها أبدًا. إذا كان ينبغي تغيير نوع المؤشر (ضعيف أو مشترك) أثناء التشغيل، استخدم طريقة [System::SmartPtr<T>::set_Mode()](./set_mode/) أو فئة [System::DynamicWeakPtr](../dynamicweakptr/). فئة [SmartPtr](./) لا تحتوي على أي طرق افتراضية. يجب أن ترثها فقط إذا كنت تنشئ استراتيجية إدارة ذاكرة خاصة بك. هذا النوع هو مؤشر لإدارة حذف كائن آخر. يجب تخصيصه على المكدس وتمريره إلى الدوال إما بالقيمة أو بالمرجع الثابت.

```cpp
template<class T>class SmartPtr
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن المشار إليه. يجب أن يكون إما [System::Object](../object/) أو فئة فرعية منه. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| auto [begin](./begin/)() | وصول إلى طريقة [begin()](./begin/) في مجموعة تحتية. يُجَمِّع فقط إذا كانت SmartPtr_ من نوع تخصص يملك طريقة [begin()](./begin/). |
| auto [begin](./begin/)() const | وصول إلى طريقة [begin()](./begin/) في مجموعة تحتية. يُجَمِّع فقط إذا كانت SmartPtr_ من نوع تخصص يملك طريقة [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | يحول المؤشر إلى نوعه نفسه. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | يحول المؤشر إلى النوع الأساسي باستخدام static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | يحول المؤشر إلى النوع المشتق باستخدام dynamic_cast. |
| auto [cbegin](./cbegin/)() const | وصول إلى طريقة [cbegin()](./cbegin/) في مجموعة تحتية. يُجَمِّع فقط إذا كانت SmartPtr_ من نوع تخصص يملك طريقة [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | وصول إلى طريقة [cend()](./cend/) في مجموعة تحتية. يُجَمِّع فقط إذا كانت SmartPtr_ من نوع تخصص يملك طريقة [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام const_cast على الكائن المشار إليه. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام dynamic_cast على الكائن المشار إليه. |
| auto [end](./end/)() | وصول إلى طريقة [end()](./end/) في مجموعة تحتية. يُجَمِّع فقط إذا كانت SmartPtr_ من نوع تخصص يملك طريقة [end()](./end/). |
| auto [end](./end/)() const | وصول إلى طريقة [end()](./end/) في مجموعة تحتية. يُجَمِّع فقط إذا كانت SmartPtr_ من نوع تخصص يملك طريقة [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | يحصل على الكائن المشار إليه. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | يحصل على وضع المؤشر. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | يحصل على الكائن المشار إليه، مع التأكد من أن المؤشر في وضع مشترك. |
| int [get_shared_count](./get_shared_count/)() const | يحصل على عدد المؤشرات المشتركة الموجودة إلى الكائن المشار إليه، بما فيها الحالي. يتأكد من أن المؤشر الحالي في وضع مشترك. |
| int [GetHashCode](./gethashcode/)() const | يستدعي [GetHashCode()](./gethashcode/) على الكائن المشار إليه. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | يحصل على الكائن المرجعي الحالي (إن وجد) أو ينتج استثناء. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | يحصل على الكائن المرجعي. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | يحصل على الكائن المشار إليه (إن وجد) أو nullptr. نفس [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن المشار إليه من النوع المحدد أو من نوع فرعي له. يتبع سلوك C# 'is'. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | يتحقق مما إذا كان المؤشر يشير إلى كائن آخر غير المملوك (تم إنشاؤه بواسطة مُنشئ التسمية). |
| **bool** [IsShared](./isshared/)() const | يتحقق مما إذا كان المؤشر في وضع مشترك. |
| **bool** [IsWeak](./isweak/)() const | يتحقق مما إذا كان المؤشر في وضع ضعيف. |
| explicit  [operator bool](./operator_bool/)() const | يتحقق مما إذا كان المؤشر غير فارغ. |
| **bool** [operator!](./operator_not/)() const | يتحقق مما إذا كان المؤشر فارغًا. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | يحصل على مرجع إلى الكائن المشار إليه. يتأكد من أن المؤشر غير فارغ. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | يتيح الوصول إلى أعضاء الكائن المرجعي. |
| **bool** [operator<](./operator_less/)(Y *) const | يقدم سلوك مقارنة أقل لفئة [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | يقدم سلوك مقارنة أقل لفئة [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | يُعَيِّن بنقل كائن [SmartPtr](./). يصبح x غير قابل للاستخدام. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | يُعَيِّن نسخة من كائن [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | يُعَيِّن نسخة من كائن [SmartPtr](./). يقوم بالتحويلات اللازمة للنوع. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | يُعيّن المؤشر الخام إلى كائن [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | يضبط قيمة المؤشر إلى nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يتحقق مما إذا كان المؤشر يشير إلى nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | يزيل التسمية (التي تم إنشاؤها بواسطة مُنشئ التسمية) من المؤشر، ويتأكد من أنه يدير (إذا كان مشتركًا) أو يتتبع (إذا كان ضعيفًا) نفس الكائن الذي يشير إليه. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | يعيّن الكائن المشار إليه. |
| void [reset](./reset/)() | يجعل المؤشر يشير إلى nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | يعيّن وضع المؤشر. قد يغيّر عدادات المراجع للكائن المرجعي. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | يستدعي طريقة SetTemplateWeakPtr() على الكائن المشار إليه (إن وجد). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | ينشئ كائن [SmartPtr](./) بالوضع المطلوب. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | ينشئ كائن [SmartPtr](./) ذي مؤشر فارغ بالوضع المطلوب. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ينشئ [SmartPtr](./) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | يُنشئ نسخة من كائن [SmartPtr](./). كلا المؤشرين يشيران إلى نفس الكائن لاحقًا. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | يُنشئ نسخة من كائن [SmartPtr](./). كلا المؤشرين يشيران إلى نفس الكائن لاحقًا. يجري تحويل النوع إذا سُمح بذلك. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | يُنشئ نسخة من كائن [SmartPtr](./) بنقل. فعليًا، يبدّل مؤشرين إذا كانا من نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | يحول نوع المصفوفة المرجعية بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان هناك تحويل نوع مصفوفة في C# غير مدعوم في C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | يهيئ مصفوفة فارغة. يستخدم لترجمة بعض بنى كود C#. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | يُنشئ [SmartPtr](./) يشارك معلومات الملكية مع القيمة الأولية للمتغيّر ptr، لكنه يحمل مؤشرًا غير مرتبط وغير مُدار p. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | يحول المؤشر إلى نوع مختلف باستخدام static_cast على الكائن المشار إليه. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | يحول أي نوع مؤشر إلى مؤشر إلى [Object](../object/). لا يتطلب أن يكون نوع Pointee_ مكتملًا. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | اختصار للحصول على كائن [System::TypeInfo](../typeinfo/) لنوع Pointee_. |
|  [~SmartPtr](./~smartptr/)() | يدمر كائن [SmartPtr](./). إذا لزم الأمر، يقلل عداد مراجع الكائن المشار إليه ويحذف الكائن. |

## تعريفات الأنواع

| النوع المعرف | الوصف |
| --- | --- |
| [Pointee_](./pointee_/) | النوع المشار إليه. |
| [SmartPtr_](./smartptr_/) | نوع مؤشر ذكي متخصص. |
| [ArrayType](./arraytype/) | نفس Pointee_، إذا كان تخصصًا لـ [System::Array](../array/)، وإلا void. |
| [ValueType](./valuetype/) | نوع التخزين للمصفوفة المشار إليها. له معنى فقط إذا كان T تخصصًا لـ [System::Array](../array/). |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)