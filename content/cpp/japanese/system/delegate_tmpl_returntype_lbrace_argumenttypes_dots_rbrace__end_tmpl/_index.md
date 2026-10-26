---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API リファレンス
description: "関数、メソッド、または関数オブジェクトへのポインタを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 287
url: /ja/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> クラス

関数、メソッド、または関数オブジェクトへのポインタを表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| ReturnType | 関数、メソッド、または関数オブジェクトへのポインタの戻り値の型を表すクラスです。 |
| ArgumentTypes | 関数、メソッド、または関数オブジェクトへのポインタが表す引数リストです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [Delegate](./delegate/)() | デフォルトコンストラクタ。何も指し示さない delegate オブジェクトを構築します。 |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | ムーブコピーコンストラクタ。指定された delegate が指すエンティティの所有権を取得します。 |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | コンストラクタ。指定されたフリーファンクションまたは静的メソッドへのポインタから delegate オブジェクトを構築します。 |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | コンストラクタ。std::bind() によって生成された関数オブジェクトへの指定ポインタから delegate を構築します。 |
|  [Delegate](./delegate/)(int, T\&) | コンストラクタ。指定された関数オブジェクトから delegate を構築します。 |
|  [Delegate](./delegate/)(long, T\&&) | ムーブコンストラクタ。指定された関数オブジェクトから delegate を構築します。 |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | コンストラクタ。指定されたオブジェクトの指定された非静的メソッドを指す delegate を構築します。 |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | コンストラクタ。指定されたオブジェクトの指定された非静的メソッドを指す delegate を構築します。 |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | std::function 関数オブジェクトを指す delegate オブジェクトを構築します。 |
| **bool** [Empty](./empty/)() const | 現在の delegate オブジェクトが空かどうかを判定します（例：任意のエンティティを指していない）。 |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 現在の delegate オブジェクトが指す関数、メソッド、または関数オブジェクトを呼び出します。 |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | ムーブ代入演算子。指定された delegate が指すエンティティの所有権を取得します。 |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | 2 つの delegate オブジェクトを比較し、同じエンティティを指しているかどうかを確認します。 |

## 備考

```cpp
#include "system/delegate.h"
#include <iostream"

// デリゲートを宣言します。
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // 変数に PrintMessage 関数のアドレスを代入します。
  Message mes = Message(&PrintMessage);

  // 関数を呼び出します。
  mes();

  return 0;
}
/*
このコード例は次の出力を生成します:
Hello, world!
*/
```

## 関連項目

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)