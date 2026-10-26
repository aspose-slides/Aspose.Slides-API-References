---
title: TypeInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل نوعًا معينًا ويوفر معلومات حوله.
type: docs
weight: 1379
url: /ar/system/typeinfo/
---
## فئة TypeInfo

يمثل نوعًا معينًا ويوفر معلومات حوله.

```cpp
class TypeInfo
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | يضيف السمة المحددة إلى قائمة سمات النوع. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | يضبط المنشئ الافتراضي للنوع T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | يضبط المنشئ الافتراضي بواسطة العامل الذي ينشئ مثيل الفئة. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | يضيف العنصر المحدد إلى قائمة عناصر النوع. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | يوفر بنية [TypeInfo](./) فريدة لنوع **BoxedValue** لتشاركها عدة فئات Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | غير مُنفَّذ. يُعيد مؤشرًا إلى التجميع الذي تم فيه إعلان النوع الممثل بواسطة الكائن الحالي. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | غير مُنفَّذ. يُعيد الاسم المؤهل بالكامل بما في ذلك اسم التجميع للنوع الممثل بواسطة الكائن الحالي. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | يُعيد مُوصف النوع الأساسي. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | يحصل على قيمة تُشير إلى ما إذا كان كائن Type الحالي يحتوي على معلمات نوع لم تُستبدل بأنواع محددة. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | يحصل على قائمة بالأعضاء الذين يحملون الاسم المحدد. |
| [String](../string/) [get_FullName](./get_fullname/)() const | يُعيد الاسم المؤهل بالكامل (بدون اسم التجميع) للنوع الممثل بواسطة الكائن الحالي. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | يحصل على مصفوفة من معاملات النوع العامة لهذا النوع. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع مجردًا ويجب تجاوزه. |
| **bool** [get_IsArray](./get_isarray/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع مصفوفة. |
| **bool** [get_IsClass](./get_isclass/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع فئة أو مُفوَّد؛ أي ليس نوع قيمة أو واجهة. |
| **bool** [get_IsEnum](./get_isenum/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع الحالي يمثل تعدادًا. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع الحالي يمثل تعريف نوع عام يمكن بناء أنواع عامة أخرى منه. |
| **bool** [get_IsInterface](./get_isinterface/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع واجهة؛ أي ليس فئة أو نوع قيمة. |
| **bool** [get_IsSealed](./get_issealed/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع مُعلنًا كختم. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | يحصل على قيمة تُشير إلى ما إذا كان النوع نوع قيمة. |
| **bool** [get_IsVisible](./get_isvisible/)() const | يحصل على قيمة تُشير إلى ما إذا كان يمكن الوصول إلى النوع من قبل شفرة خارج التجميع. |
| [String](../string/) [get_Name](./get_name/)() const | يُعيد اسم النوع الممثل بواسطة الكائن الحالي. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | يحصل على مساحة أسماء النوع. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | يبحث عن منشئ نسخة عام يمكن الوصول إليه وتطابق معلماته الأنواع الموجودة في المصفوفة المحددة. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | يبحث عن المنشئين المحددين للنوع الحالي باستخدام BindingFlags المحدد. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | يُعيد جميع المنشئين العامين المحددين للنوع الحالي. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | يبحث عن السمة المخصصة المُطبقة من النوع المحدد والمطبقة على النوع الممثل بالكائن الحالي. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | يُعيد مصفوفة تحتوي على كائنات تمثل جميع السمات المخصصة المطبقة على النوع. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | يُعيد مصفوفة تحتوي على كائنات تمثل سمات محددة مطبقة على النوع. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | غير مُنفَّذ. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | يبحث عن الحقل المحدد باستخدام قيود الربط المحددة. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | يبحث عن الحقول المعرفة للنوع الحالي باستخدام قيود الربط المحددة. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | يحصل على مصفوفة من معاملات النوع العامة لهذا النوع. |
| int [GetHashCode](./gethashcode/)() const | يُعيد رمز تجزئة مرتبط بهذه المثيلة. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | يحصل على جميع الواجهات المُنفذة أو الموروثة من النوع الحالي. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | يحصل على قائمة بالأعضاء الذين يحملون الاسم المحدد. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | يحصل على الطريقة التي تحمل الاسم المحدد. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | يُعيد جميع الخصائص العامة للنوع الحالي. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | يبحث عن خصائص النوع الحالي باستخدام قيود الربط المحددة. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | يحصل على موصف نوع معامل القالب. |
| **uint32_t** [Hash](./hash/)() const | يُعيد قيمة تجزئة مرتبطة بالنوع الممثل بواسطة الكائن الحالي. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | يحدِّد ما إذا كان يمكن تعيين مثيل من نوع محدد إلى متغيّر من النوع الحالي. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | غير مُنفَّذ. يُشير إلى ما إذا كانت سمة واحدة أو أكثر من النوع المحدد أو من أنواعه المشتقة مُطبقة على هذا العضو. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يحدِّد ما إذا كان الكائن المحدد مثالًا على النوع الحالي. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | يحدِّد ما إذا كان النوع الممثل بواسطة الكائن الحالي هو فئة فرعية من الفئة المحددة. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | يحدِّد ما إذا كان الكائنان [TypeInfo](./) الحالي والمحدد غير متساويين. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | يحدِّد ما إذا كان كائن [TypeInfo](./) الحالي ليس كائنًا فارغًا، أي أنه يمثل نوعًا ما. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | يحدِّد ما إذا كان الكائنان [TypeInfo](./) الحالي والمحدد متساويين. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يحدِّد ما إذا كان كائن [TypeInfo](./) الحالي هو كائن فارغ، أي لا يمثل أي نوع. |
| void [reset](./reset/)() | يضبط [TypeInfo](./) إلى null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | يضبط قيمة تُشير إلى ما إذا كان النوع نوع قيمة. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | يضبط موصف النوع الأساسي. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | يضبط موصف نوع معامل القالب. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | يحسب التجزئة للسلسلة المحددة. |
| [String](../string/) [ToString](./tostring/)() const | يُعيد سلسلة تحتوي على اسم النوع الممثل بواسطة الكائن الحالي. |
| static const [TypeInfo](./)\& [Type](./type/)() | يُعيد كائن [TypeInfo](./) يمثل الفئة [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | منشئ افتراضي (لم يتم تعيين نوع). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | منشئ كائن فارغ (لم يتم تعيين نوع). |
|  [TypeInfo](./typeinfo/)(const char_t *) | منشئ. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | منشئ. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | منشئ. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [EmptyType](./emptytype/) | ثابت يمثل قائمة فارغة من [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | ثابت يمثل قائمة فارغة من [TypeInfo](./). |

## تعريفات النوع

| تعريف النوع | الوصف |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | مؤشر دالة لإنشاء النوع. |

## انظر أيضًا

* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)