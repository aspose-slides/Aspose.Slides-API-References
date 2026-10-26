---
title: ObjectType
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクト型ゲッターを実装する静的メソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。
type: docs
weight: 1158
url: /ja/system/objecttype/
---
## ObjectType クラス

オブジェクト型ゲッターを実装する静的メソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。

```cpp
class ObjectType
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() の変換を実装します。スマートポインタ用のオーバーロードです。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() の変換を実装します。構造体用のオーバーロードです。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() の変換を実装します。例外用のオーバーロードです。 |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() の変換を実装します。プリミティブ型用のオーバーロードです。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() の変換を実装します。[Nullable](../nullable/) 型用のオーバーロードです。 |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() の変換を実装します。プリミティブ型用のオーバーロードです。 |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() の変換を実装します。enum 型用のオーバーロードです。 |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() の変換を実装します。構造体とポインタ用のオーバーロードです。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() の変換を実装します。[Nullable](../nullable/) 用のオーバーロードです。 |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() の変換を実装します。MutlicastDelegate 用のオーバーロードです。 |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() の変換を実装します。構造体とポインタ用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | typeof() の変換を実装します。文字列型用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() の変換を実装します。**uint8_t** 用のオーバーロードです。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)