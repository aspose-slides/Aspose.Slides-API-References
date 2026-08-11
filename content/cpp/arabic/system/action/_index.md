---
title: Action
second_title: مرجع API لـ Aspose.Slides للغة C++
description: نوع المفوض الذي يشير إلى الأساليب التي لا تُعيد قيمة.
type: docs
weight: 3602
url: /ar/system/action/
---
## تعريف نوع Action


نوع المفوض الذي يشير إلى الأساليب التي لا تُعيد قيمة.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## ملاحظات



```cpp
#include <system/action.h>

using namespace System;

// الدالة التي تطبع السلسلة المرسلة.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // إنشاء نسخة من Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // استدعاء الـ action.
  action(u"Hello, world!");

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
مرحبًا، العالم!
*/
```

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)