---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides لـ C++ مرجع API
description: 
type: docs
weight: 287
url: /ar/system.boxedvaluedetail/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Comparable](./comparable/) | تنفيذ بسيط لـ IComparable<> |
| [NonComparable](./noncomparable/) | نوع أساسي تجريبي للأنواع المعبأة التي لا تنفّذ IComparable<> |

## الهياكل

| الهيكل | الوصف |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | دالة شرط قالبية تتحقق مما إذا كان يجب على الكائن المعبأ تنفيذ الواجهة المعطاة بنفسه. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) ينفّذ [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | دالة شرط قالبية تتحقق مما إذا كان يجب على الكائن المعبأ تنفيذ واجهة [IComparable](../system/icomparable/) بنفسه. |

## الدوال

| الدالة | الوصف |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | يحدد مساواة القيمة المحددة باستخدام [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | يحدد مساواة القيمة المحددة باستخدام الطريقة [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | يقارن قيمتين عائمة ذات دقة مفردة. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | يقارن قيمتين عائمة ذات دقة مزدوجة. |