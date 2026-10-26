---
title: ObjectExt
second_title: Aspose.Slides for C++ API リファレンス
description: 非オブジェクト C++ 型（文字列、数値など）に対して呼び出される C# Object メソッドをエミュレートする静的メソッドを提供します。この型はインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。
type: docs
weight: 1145
url: /ja/system/objectext/
---
## ObjectExt クラス

非オブジェクト C++ 型（文字列、数値など）に対して呼び出される C# [Object](../object/) メソッドをエミュレートする静的メソッドを提供します。この型はインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。

```cpp
class ObjectExt : public System::ObjectType
```

## メソッド

| Method | 説明 |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | 配列の基本型の値を変換します（C# では暗黙的に行われますが、C++ では明示的に行う必要があります）。 |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Object](../object/) に変換するために値型をボックス化します。enum 型の実装です。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Object](../object/) に変換するために値型をボックス化します。非 enum 型の実装です。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Nullable](../nullable/) 型を [Object](../object/) に変換するためにボックス化します。 |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | 文字列値をボックス化します。 |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | enum 型を [Object](../object/) として伝搬させるためにボックス化します。 |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | 非 nullable 型に対する '??' 演算子の翻訳を実装します。 |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | nullable 型に対する '??' 演算子の翻訳を実装します。 |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | '??=' 演算子の翻訳を実装します。 |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | 非 nullable 型に対する '??' 演算子の翻訳を実装します。RT2 が RT1 に変換可能な場合のオーバーロードです。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) 呼び出しの代替実装で、C++ の任意の型で動作します。スマートポインタ型用のオーバーロードです。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | C# [Object.Equals](../object/equals/) 呼び出しの代替実装で、C++ の任意の型で動作します。構造体型用のオーバーロードです。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) 呼び出しの代替実装で、C++ の任意の型で動作します。スカラ型用のオーバーロードです。 |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | C# [Object.Equals](../object/equals/) 呼び出しの代替実装で、C++ の任意の型で動作します。文字列リテラルの文字列比較用のオーバーロードです。 |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、二つの NaN を等しいとみなします。 |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | IEC 60559:1989 によれば NaN は任意の値（NaN 含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、二つの NaN を等しいとみなします。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | [GetHashCode()](./gethashcode/) 呼び出しを実装します。[Object](../object/) のサブクラスと無関係な型の両方で機能します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() の翻訳を実装します。スマートポインタ用のオーバーロードです。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() の翻訳を実装します。構造体用のオーバーロードです。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() の翻訳を実装します。例外用のオーバーロードです。 |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() の翻訳を実装します。プリミティブ型用のオーバーロードです。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() の翻訳を実装します。[Nullable](../nullable/) 型用のオーバーロードです。 |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。プリミティブ型用のオーバーロードです。 |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。enum 型用のオーバーロードです。 |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。構造体およびポインタ用のオーバーロードです。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。[Nullable](../nullable/) 用のオーバーロードです。 |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。MutlicastDelegate 用のオーバーロードです。 |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。構造体およびポインタ用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | typeof() の翻訳を実装します。文字列型用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() の翻訳を実装します。**uint8_t** 用のオーバーロードです。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | 'is' 演算子の翻訳を実装します。ボックス可能な（値）型に対する特殊化で、正確にそれらが該当します。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' 演算子の翻訳を実装します。'final' クラスに最適化されたポインタ型に対する特殊化です。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' 演算子の翻訳を実装します。ポインタ型に対する特殊化です。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' 演算子の翻訳を実装します。値型に対する特殊化です。 |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' 演算子の翻訳を実装します。変換不可能な型に対する特殊化です。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' 演算子の翻訳を実装します。ポインタ型に対する特殊化です。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | 'is' 演算子の翻訳を実装します。例外ラッパー型に対する特殊化です。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' 演算子の翻訳を実装します。nullable 型に対する特殊化です。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' 演算子の翻訳を実装します。== 演算子が定義されたボックス可能な型に対する特殊化です。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' 演算子の翻訳を実装します。== が定義されていないボックス可能な型に対する特殊化です。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | 'is' 演算子の翻訳を実装します。インターフェイスにボックスされた値型に対する特殊化です。 |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' 演算子の翻訳を実装します。enum 型に対する特殊化です。 |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | 'is' 演算子の翻訳を実装します。enum 型と弱ポインタの特殊化です。 |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | 'is' 演算子の翻訳を実装します。[Nullable](../nullable/) 型に対する特殊化です。 |
| static **bool** [Is](./is/)(const char16_t *) | 'is' 演算子の翻訳を実装します。文字列リテラルに対する特殊化です。 |
| static **bool** [Is](./is/)(**int32_t**) | 'is' 演算子の翻訳を実装します。整数リテラルに対する特殊化です。 |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | オブジェクトがボックス化された値かどうかをチェックします。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/) を未知の型に変換し、スマートポインタ型とボックス化された値の両方の状況を処理します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/) を未知の型に変換し、スマートポインタ型とボックス化された値の両方の状況を処理します。 |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | 任意の C++ 型で機能する C# の ToString メソッドの代替実装です。 |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) に変換した後、値型をアンボックスします。enum 型の実装です。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) に変換した後、値型をアンボックスします。enum ではなく nullable でもない型の実装です。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) に変換した後、値型をアンボックスします。enum ではなく nullable でもない型の実装です。 |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | enum 型を整数にアンボックスします。 |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | enum 型を変換します。 |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 文字列値をアンボックスします。 |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ボックス化された値から文字列をアンボックスします。 |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | オブジェクトを nullable 型にアンボックスします。 |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 未知の型オブジェクトが nullptr かどうかをチェックします。非スカラ型用のオーバーロードです。 |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 未知の型オブジェクトが nullptr かどうかをチェックします。スカラ型用のオーバーロードです。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | 未知の型を [Object](../object/) に変換し、スマートポインタ型と値型の両方の状況を処理します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | 未知の型を [Object](../object/) に変換し、スマートポインタ型と値型の両方の状況を処理します。 |

## 参照

* クラス [ObjectType](../objecttype/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)