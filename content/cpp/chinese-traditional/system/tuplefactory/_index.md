---
title: TupleFactory
second_title: Aspose.Slides for C++ API 參考文件
description: 提供用於建立 tuple 物件的靜態方法。
type: docs
weight: 1366
url: /zh-hant/system/tuplefactory/
---
## TupleFactory 類別


提供用於建立 tuple 物件的靜態方法。

```cpp
class TupleFactory
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | 建立新的元組物件。 |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | 建立新的 8-元組。第 8 個元素儲存在 [Tuple](../tuple/) 中。 |
## 備註



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
此程式碼範例會產生以下輸出：
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)