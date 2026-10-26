---
title: Func()
second_title: مرجع API Aspose.Slides برای C++
description: سازنده پیش‌فرض که یک null-Func ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system/func/func/
---
## Func::Func() سازنده

سازنده پیش‌فرض که یک null-Func ایجاد می‌کند.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) سازنده

سازنده‌ای که شی [Func](../) را می‌سازد و مقدار (یا callback واقعی یا nullptr) را به آن اختصاص می‌دهد.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع آرگومان. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arg | T\&& | آرگومان. |

## Func::Func(const Func\&) سازنده

سازنده کپی.

```cpp
System::Func<Args>::Func(const Func &func)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) برای کپی کردن داده‌ها از. |

## Func::Func(Func\&&) سازنده

سازنده جابجایی.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) برای انتقال داده‌ها از. |

## موارد مرتبط

* کلاس [Func](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)