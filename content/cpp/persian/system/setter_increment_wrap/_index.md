---
title: setter_increment_wrap()
second_title: Aspose.Slides برای C++ مرجع API
description: مترجم عبارات افزایشی C# که به ویژگی کلاس با setter و getter تعریف‌شده هدف می‌گیرند را به فراخوانی این تابع تبدیل می‌کند.
type: docs
weight: 2835
url: /fa/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) تابع

مترجم عبارات افزایشی C# که به ویژگی کلاس با setter و getter تعریف‌شده هدف می‌گیرند را به فراخوانی این تابع تبدیل می‌کند.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pGetter | T(*)() | اشاره‌گر تابعی که به تابع آزاد getter ویژگی اشاره می‌کند |
| pSetter | void(*)(T) | اشاره‌گر تابعی که به تابع آزاد setter ویژگی اشاره می‌کند |

### مقدار بازگشت

مقدار افزایشی ویژگی

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) تابع

مترجم عبارات افزایشی C# که به ویژگی کلاس با setter و getter تعریف‌شده هدف می‌گیرند را به فراخوانی این تابع تبدیل می‌کند.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |
| Host | - کلاس نمونه‌ای که باید تغییر داده شود |
| HostGet | - خود Host یا نوع پایه‌اش که در آن getter ویژگی تعریف شده است |
| HostSet | - خود Host یا نوع پایه‌اش که در آن setter ویژگی تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | یک اشاره‌گر به شیئی که ویژگی آن باید افزوده شود |
| pGetter | T(HostGet::*)() | اشاره‌گر تابعی که به متد getter ویژگی اشاره می‌کند |
| pSetter | void(HostSet::*)(T) | اشاره‌گر تابعی که به متد setter ویژگی اشاره می‌کند |

### مقدار بازگشت

مقدار افزایشی ویژگی

## همچنین ببینید

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)