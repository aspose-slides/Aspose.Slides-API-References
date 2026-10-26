---
title: Predicate
second_title: Aspose.Slides for C++ API リファレンス
description: 述語へのポインタを表します - 単一の引数を受け取り、bool 値を返す呼び出し可能エンティティです。
type: docs
weight: 4187
url: /ja/system/predicate/
---
## 述語型定義

述語へのポインタを表します - 単一の引数を受け取り、bool 値を返す呼び出し可能エンティティです。

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## 備考



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // 配列を埋めます。
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // 3 より大きい配列要素を返す述語を作成します。
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // 作成した述語を使って配列の最初の要素を検索し、出力します。
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
このコード例は以下の出力を生成します：
5
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)