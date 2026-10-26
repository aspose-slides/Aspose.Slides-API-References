---
title: Func
second_title: مرجع API Aspose.Slides برای C++
description: "نمایندهٔ تابع. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 859
url: /fa/system/func/
---
## Func کلاس


نماینده تابع. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Args | آرگومان‌های فراخوانی، سپس نوع بازگشت الزامی. |
## متدها

| متد | توضیح |
| --- | --- |
|  [Func](./func/)() | سازندهٔ پیش‌فرض که یک null-Func ایجاد می‌کند. |
|  [Func](./func/)(T\&&) | سازنده‌ای که شیء [Func](./) را می‌سازد و مقدار (یا کال‌بک واقعی یا nullptr) را به آن اختصاص می‌دهد. |
|  [Func](./func/)(const [Func](./)\&) | سازندهٔ کپی. |
|  [Func](./func/)([Func](./)\&&) | سازندهٔ انتقال. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | اختصاص کپی. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | اختصاص انتقال. |
|  [~Func](./~func/)() | تخریب‌کننده. |
## یادداشت‌ها



```cpp
#include "system/func.h"
#include <iostream>

// این تابع یک نمونه از نماینده System::Func را به عنوان پارامتر می‌پذیرد.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // یک نمونه از نماینده System::Func ایجاد کنید.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // نمونهٔ ایجاد شده را به عنوان آرگومان تابع منتقل کنید.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
1
4
9
*/
```

## مشاهده نیز

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)