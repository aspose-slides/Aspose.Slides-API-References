---
title: DoTryFinally()
second_title: Aspose.Slides برای C++ مرجع API
description: تابع تک که رفتار عبارت try[-catch]-finally زبان C# را شبیه‌سازی می‌کند. در هنگام ترجمه عبارت try[-catch]-finally زبان C# با گزینه ترجمه‌کننده finally_statement_as_lambda تنظیم‌شده به true، این عبارت به فراخوانی این متد ترجمه می‌شود.
type: docs
weight: 2445
url: /fa/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) تابع

تابع تک که رفتار عبارت try[-catch]-finally زبان C# را شبیه‌سازی می‌کند. در هنگام ترجمه عبارت try[-catch]-finally زبان C# با گزینه ترجمه‌کننده finally_statement_as_lambda تنظیم‌شده به true، این عبارت به فراخوانی این متد ترجمه می‌شود.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء تابعی که بخش try[-catch] عبارت try[-catch]-finally شبیه‌سازی شده را پیاده‌سازی می‌کند |
| F | نوع شیء تابعی که بخش finally عبارت try[-catch]-finally شبیه‌سازی شده را پیاده‌سازی می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tryBlock | T\&& | شیء تابعی که بدنه‌اش شامل پیاده‌سازی بخش try[-catch] عبارت try[-catch]-finally شبیه‌سازی شده است |
| finallyBlock | F\&& | شیء تابعی که بدنه‌اش شامل پیاده‌سازی بخش finally عبارت try[-catch]-finally شبیه‌سازی شده است |

## System::DoTryFinally(T\&&, F\&&) تابع

تابع تک که رفتار عبارت try[-catch]-finally زبان C# را شبیه‌سازی می‌کند. در هنگام ترجمه عبارت try[-catch]-finally زبان C# با گزینه ترجمه‌کننده finally_statement_as_lambda تنظیم‌شده به true، این عبارت به فراخوانی این متد ترجمه می‌شود. این بارگذاری موردی را پوشش می‌دهد که مقدار بازگشتی شیء تابعی که بخش try[-catch] عبارت try[-catch]-finally را پیاده‌سازی می‌کند، نوع bool است.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء تابعی که بخش try[-catch] عبارت try[-catch]-finally شبیه‌سازی شده را پیاده‌سازی می‌کند |
| F | نوع شیء تابعی که بخش finally عبارت try[-catch]-finally شبیه‌سازی شده را پیاده‌سازی می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tryBlock | T\&& | شیء تابعی که بدنه‌اش شامل پیاده‌سازی بخش try[-catch] عبارت try[-catch]-finally شبیه‌سازی شده است |
| finallyBlock | F\&& | شیء تابعی که بدنه‌اش شامل پیاده‌سازی بخش finally عبارت try[-catch]-finally شبیه‌سازی شده است |

## System::DoTryFinally(T\&&, F\&&) تابع

تابع تک که رفتار عبارت try[-catch]-finally زبان C# را شبیه‌سازی می‌کند. در هنگام ترجمه عبارت try[-catch]-finally زبان C# با گزینه ترجمه‌کننده finally_statement_as_lambda تنظیم‌شده به true، این عبارت به فراخوانی این متد ترجمه می‌شود. این بارگذاری موردی را پوشش می‌دهد که مقدار بازگشتی شیء تابعی که بخش try[-catch] عبارت try[-catch]-finally را پیاده‌سازی می‌کند، نوع bool& است.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء تابعی که بخش try[-catch] عبارت try[-catch]-finally شبیه‌سازی شده را پیاده‌سازی می‌کند |
| F | نوع شیء تابعی که بخش finally عبارت try[-catch]-finally شبیه‌سازی شده را پیاده‌سازی می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| tryBlock | T\&& | شیء تابعی که بدنه‌اش شامل پیاده‌سازی بخش try[-catch] عبارت try[-catch]-finally شبیه‌سازی شده است |
| finallyBlock | F\&& | شیء تابعی که بدنه‌اش شامل پیاده‌سازی بخش finally عبارت try[-catch]-finally شبیه‌سازی شده است |

## مراجع

* Namespace [System](../)
* Library [Aspose.Slides](../../)