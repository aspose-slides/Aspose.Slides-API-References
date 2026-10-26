---
title: Comparison
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک اشاره‌گر به متدی است که دو شیء از یک نوع را مقایسه می‌کند. این نوع باید بر روی پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیای این نوع استفاده نکنید."
type: docs
weight: 183
url: /fa/system/comparison/
---
## Comparison کلاس

نشان‌گر به متدی را نمایان می‌کند که دو شیء از یک نوع را مقایسه می‌کند. این نوع باید روی پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیای این نوع استفاده نکنید.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشیائی که متد آنها را مقایسه می‌کند |

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | شیء قابل فراخوانی که توسط شیء جاری اشاره شده است را فراخوانی می‌کند. |

## توضیحات



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// کلاس قالب که نمایانگر یک آرایهٔ پویا است.
template <typename T>
class MyArray
{
  // برای ذخیره داده‌های آرایه استفاده می‌شود.
  std::vector<T> m_data;

public:
  // یک نمونه جدید از آرایهٔ پویا ما را می‌سازد.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // برای مرتب‌سازی داده‌های آرایه استفاده می‌شود. این متد یک نمونه از
  // کلاس قالب 'System::Comparison' را می‌پذیرد.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // تعداد عناصری را که آرایهٔ پویا ما ذخیره می‌کند برمی‌گرداند.
  size_t get_Size()
  {
    return m_data.size();
  }

  // برای دریافت یک عنصر در اندیس مشخص استفاده می‌شود.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // یک نمونه از کلاس MyArray با عناصر مشخص ایجاد می‌کند.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // به‌صورت صعودی عناصر آرایهٔ پویا را مرتب می‌کند.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // عناصر آرایهٔ پویا را چاپ می‌کند.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
a
b
c
d
e
*/
```

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)