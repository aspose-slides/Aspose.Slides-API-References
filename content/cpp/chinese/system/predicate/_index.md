---
title: Predicate
second_title: Aspose.Slides for C++ API 参考
description: 表示指向 predicate 的指针——一个可调用实体，接受单个参数并返回 bool 值。
type: docs
weight: 4148
url: /zh/system/predicate/
---
## Predicate typedef

表示指向 predicate 的指针——一个可调用实体，接受单个参数并返回 bool 值。

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## 备注



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // 填充数组。
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // 创建返回大于3的数组元素的谓词。
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // 使用创建的谓词查找数组的第一个元素并打印它。
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
此代码示例产生以下输出：
5
*/
```

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)