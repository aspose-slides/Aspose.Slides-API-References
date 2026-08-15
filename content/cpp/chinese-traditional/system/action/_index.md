---
title: Action
second_title: Aspose.Slides for C++ API 參考手冊
description: 委託類型，參照沒有返回值的方法。
type: docs
weight: 3602
url: /zh-hant/system/action/
---
## Action 型別定義


委託類型，參照沒有返回值的方法。

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## 備註



```cpp
#include <system/action.h>

using namespace System;

// 打印傳入字串的函式。
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // 建立 Action 的實例。
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // 呼叫 action。
  action(u"Hello, world!");

  return 0;
}
/*
此程式碼範例會產生以下輸出:
Hello, world!
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)