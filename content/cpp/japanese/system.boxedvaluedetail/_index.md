---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 287
url: /ja/system.boxedvaluedetail/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [Comparable](./comparable/) | IComparable<> のシンプルな実装 |
| [NonComparable](./noncomparable/) | IComparable<> を実装しないボックス化型のダミーベース型 |
## 構造体

| 構造体 | 説明 |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | ボックス化されたオブジェクトが自ら指定されたインターフェイスを実装すべきかをチェックするテンプレート述語 |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) は [IComparable](../system/icomparable/) を実装します。 |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | ボックス化されたオブジェクトが自ら [IComparable](../system/icomparable/) インターフェイスを実装すべきかをチェックするテンプレート述語 |
## 関数

| 関数 | 説明 |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | [operator==()](../system/operator_equal_equal/) を使用して指定された値の等価性を判断します。 |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | [System::Object::Equals()](../system/object/equals/) メソッドを使用して指定された値の等価性を判断します。 |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | 単精度浮動小数点値を2つ比較します。 |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | 倍精度浮動小数点値を2つ比較します。 |