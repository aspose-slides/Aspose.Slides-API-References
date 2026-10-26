---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ APIリファレンス
description: "デリゲートのコレクションを表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 1093
url: /ja/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> クラス


デリゲートのコレクションを表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| ReturnType | コレクション内の各デリゲートが指す呼び出し可能エンティティの戻り値の型 |
| ArgumentTypes | コレクション内の各デリゲートが指す呼び出し可能エンティティの引数リスト |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | 未実装 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | 指定されたデリゲートをコレクションに追加します。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | 指定された関数オブジェクトをデリゲートコレクションに追加します。関数オブジェクトは、コレクションに追加される前に Callback デリゲート型に変換されます。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | 指定された MulticastDelegate オブジェクトをデリゲートコレクションに追加します。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | 指定されたオブジェクトの非静的メソッドをデリゲートコレクションに追加します。 |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 指定されたオブジェクトの非静的メソッドをデリゲートコレクションに追加します。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | 指定されたデリゲートをデリゲートコレクションから削除します。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | 指定されたオブジェクトの非静的メソッドをデリゲートコレクションから削除します。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 指定されたオブジェクトの非静的メソッドをデリゲートコレクションから削除します。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | 指定された MulticastDelegate オブジェクトをデリゲートコレクションから削除します。 |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | デリゲートコレクションからすべてのデリゲートを削除します。 |
| **bool** [empty](./empty/)() const | デリゲートコレクションが空であるかどうかを判定します。 |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | 未実装 |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | 現在コレクションに存在するすべてのデリゲートを呼び出します。デリゲートはコレクションに追加された順序で呼び出されます。メソッドはデリゲートの実行中ブロックします。 |
| **bool** [IsNull](./isnull/)() const | デリゲートコレクションが空であるかどうかを判定します。 |
|  [MulticastDelegate](./multicastdelegate/)() | 空のコレクションを構築します。 |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | デフォルトコンストラクタと同等です。 |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | デリゲートコレクションの浅いコピーを実行します。 |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | ムーブコンストラクタ。 |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | インスタンスを構築し、指定されたデリゲートをデリゲートコレクションに追加します。 |
|  [MulticastDelegate](./multicastdelegate/)(T) | インスタンスを構築し、指定された値をデリゲートコレクションに追加します。 |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | インスタンスを構築し、指定された値をデリゲートコレクションに追加します。 |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | デリゲートコレクションが空でないかどうかを判定します。 |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 現在のオブジェクトと指定されたオブジェクトという 2 つの MulticastDelegate インスタンスが等しくないかどうかを判定します。 |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 現在コレクションに存在するすべてのデリゲートを呼び出します。デリゲートはコレクションに追加された順序で呼び出されます。演算子はデリゲートの実行中ブロックします。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | 指定されたデリゲートをコレクションに追加します。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | 指定されたデリゲートをデリゲートコレクションから削除します。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | 指定されたオブジェクトが表すデリゲートのコレクションを現在のオブジェクトに割り当てます。その結果、両オブジェクトは同じデリゲートコレクションを指します。 |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | ムーブ代入演算子。 |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | デリゲートコレクションが空であるかどうかを判定します。 |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | 現在のオブジェクトと指定されたオブジェクトという 2 つの MulticastDelegate インスタンスが等しいかどうかを判定します。 |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | 空のコールバック（実際に何も呼び出さない）を除去します。 |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) オブジェクト（MulticastDelegate クラスの型情報を表す）への参照を返します。 |
|  [~MulticastDelegate](./~multicastdelegate/)() | デストラクタ。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [Callback](./callback/) | MulticastDelegate クラスが表すデリゲートの型です。 |
| [Function](./function/) | デリゲートシグネチャに関連する関数の型です。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)