---
title: Action
second_title: Aspose.Slides for C++ API 参考
description: 委托类型，引用没有返回值的方法。
type: docs
weight: 3563
url: /zh/system/action/
---
## Action 类型别名


委托类型，引用没有返回值的方法。

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## 备注



```cpp
#include <system/action.h>

using namespace System;

// 函数，用于打印传入的字符串。
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // 创建 Action 实例。
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // 调用该 Action。
  action(u"Hello, world!");

  return 0;
}
/*
此代码示例产生以下输出：
Hello, world!
*/
```

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)