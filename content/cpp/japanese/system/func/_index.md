---
title: Func
second_title: Aspose.Slides for C++ API リファレンス
description: "関数デリゲート。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。この型のオブジェクトを管理するために System::SmartPtr クラスを使用しないでください。"
type: docs
weight: 859
url: /ja/system/func/
---
## Func クラス

関数デリゲート。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。 この型のオブジェクトを管理するために [System::SmartPtr](../smartptr/) クラスを使用しないでください。

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Args | 呼び出し引数、続いて必須の戻り値型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [Func](./func/)() | デフォルトコンストラクタで、null-Func を作成します。 |
|  [Func](./func/)(T\&&) | [Func](./) オブジェクトを構築し、その値（実際のコールバックまたは nullptr のいずれか）を割り当てるコンストラクタです。 |
|  [Func](./func/)(const [Func](./)\&) | コピーコンストラクタ。 |
|  [Func](./func/)([Func](./)\&&) | ムーブコンストラクタ。 |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | コピー代入演算子。 |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | ムーブ代入演算子。 |
|  [~Func](./~func/)() | デストラクタ。 |

## 備考

```cpp
#include "system/func.h"
#include <iostream"

// この関数は System::Func デリゲートのインスタンスをパラメータとして受け取ります。
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // System::Func デリゲートのインスタンスを作成します。
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // 作成したインスタンスを関数引数として渡します。
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
このコード例は次の出力を生成します。
1
4
9
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)