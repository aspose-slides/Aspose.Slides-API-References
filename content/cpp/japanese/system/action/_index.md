---
title: Action
second_title: Aspose.Slides for C++ API リファレンス
description: 戻り値を持たないメソッドを参照するデリゲート型です。
type: docs
weight: 3602
url: /ja/system/action/
---
## Action typedef


Delegate type that references methods that have no return value.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## 備考



```cpp
#include <system/action.h>

using namespace System;

// 渡された文字列を出力する関数です。
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Action のインスタンスを作成します。
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // action を呼び出します。
  action(u"Hello, world!");

  return 0;
}
/*
このコード例は以下の出力を生成します：
こんにちは、世界！
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)