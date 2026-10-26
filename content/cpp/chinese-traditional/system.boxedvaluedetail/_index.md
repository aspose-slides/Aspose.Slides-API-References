---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 287
url: /zh-hant/system.boxedvaluedetail/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [Comparable](./comparable/) | IComparable<> 的簡單實作 |
| [NonComparable](./noncomparable/) | 未實作 IComparable<> 的封裝類型的虛擬基礎型別 |
## 結構

| 結構 | 描述 |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | 模板謂詞，用於檢查封裝物件是否應自行實作給定介面。 |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) 實作 [IComparable](../system/icomparable/)。 |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | 模板謂詞，用於檢查封裝物件是否應自行實作 [IComparable](../system/icomparable/) 介面。 |
## 函式

| 函式 | 描述 |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | 使用 [operator==()](../system/operator_equal_equal/) 判斷指定值的相等性。 |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | 使用 [System::Object::Equals()](../system/object/equals/) 方法判斷指定值的相等性。 |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | 比較兩個單精度浮點數值。 |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | 比較兩個雙精度浮點數值。 |