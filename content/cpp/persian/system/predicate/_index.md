---
title: Predicate
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر اشاره‌گری به یک پیش‌شرط – یک موجودیت قابل فراخوانی که یک آرگومان واحد می‌گیرد و مقدار bool را برمی‌گرداند.
type: docs
weight: 4187
url: /fa/system/predicate/
---
## تعریف نوع پیش‌شرط

نمایانگر اشاره‌گری به یک پیش‌شرط – یک موجودیت قابل فراخوانی که یک آرگومان واحد می‌گیرد و مقدار bool را برمی‌گرداند.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## توضیحات


```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // پر کردن آرایه.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // ایجاد پیش‌شرطی که عنصری از آرایه بزرگ‌تر از ۳ را برمی‌گرداند.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // یافتن اولین عنصر آرایه با استفاده از پیش‌شرط ایجاد شده و چاپ آن.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
5
*/
```

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)