---
title: Predicate
second_title: Aspose.Slides for C++ API 參考文件
description: 表示指向謂詞的指標 - 可接受單一參數並回傳 bool 值的可呼叫實體。
type: docs
weight: 4187
url: /zh-hant/system/predicate/
---
## Predicate 型別定義


表示指向謂詞的指標 - 可接受單一參數並回傳 bool 值的可呼叫實體。

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## 備註



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // 填充陣列。
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // 建立傳回大於 3 的陣列元素的謂詞。
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // 使用已建立的謂詞尋找陣列的第一個元素並印出。
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
此程式碼範例會產生以下輸出：
5
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)