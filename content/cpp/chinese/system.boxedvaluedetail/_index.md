---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 287
url: /zh/system.boxedvaluedetail/
---
## Classes

| 类 | 描述 |
| --- | --- |
| [Comparable](./comparable/) | IComparable<> 的简单实现 |
| [NonComparable](./noncomparable/) | 用于未实现 IComparable<> 的装箱类型的虚拟基类 |
## Structures

| 结构体 | 描述 |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | 用于检查装箱对象是否应自行实现给定接口的模板谓词。 |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) 实现 [IComparable](../system/icomparable/)。 |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | 用于检查装箱对象是否应自行实现 [IComparable](../system/icomparable/) 接口的模板谓词。 |
## Functions

| 函数 | 描述 |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | 使用 [operator==()](../system/operator_equal_equal/) 确定指定值的相等性。 |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | 使用方法 [System::Object::Equals()](../system/object/equals/) 确定指定值的相等性。 |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | 比较两个单精度浮点值。 |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | 比较两个双精度浮点值。 |