---
title: TupleFactory
second_title: Aspose.Slides for C++ API 参考
description: 提供用于创建元组对象的静态方法。
type: docs
weight: 1340
url: /zh/system/tuplefactory/
---
## TupleFactory 类

提供用于创建元组对象的静态方法。

```cpp
class TupleFactory
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | 创建一个新的元组对象。 |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | 创建一个新的 8 元组。第 8 个元素存储在 [Tuple](../tuple/) 中。 |
## 备注

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
此代码示例产生以下输出：
项目 1: 256
项目 2: 16
项目 3: 64
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)