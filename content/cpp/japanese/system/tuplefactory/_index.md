---
title: TupleFactory
second_title: Aspose.Slides for C++ API リファレンス
description: タプル オブジェクトを作成するための静的メソッドを提供します。
type: docs
weight: 1366
url: /ja/system/tuplefactory/
---
## TupleFactory クラス

タプル オブジェクトを作成するための静的メソッドを提供します。

```cpp
class TupleFactory
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | 新しいタプル オブジェクトを作成します。 |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | 新しい 8 タプルを作成します。8 番目の要素は [Tuple](../tuple/) に格納されます。 |
## 備考

```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
このコード例は次の出力を生成します:
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)