---
title: Action
second_title: مرجع API Aspose.Slides برای C++
description: نوع تفویض که به متدهایی که مقدار بازگشتی ندارند ارجاع می‌دهد.
type: docs
weight: 3602
url: /fa/system/action/
---
## Action typedef


نوع تفویض که به متدهایی که مقدار بازگشتی ندارند ارجاع می‌دهد.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## توضیحات



```cpp
#include <system/action.h>

using namespace System;

//  تابعی که رشته‌ی ارسال‌شده را چاپ می‌کند.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  //  یک نمونه از Action ایجاد می‌کند.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  //  عملکرد Action را فراخوانی می‌کند.
  action(u"Hello, world!");

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
سلام، جهان!
*/
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)