---
title: MulticastDelegate()
second_title: مرجع API Aspose.Slides برای C++
description: یک مجموعه خالی می‌سازد.
type: docs
weight: 1
url: /fa/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() متد

یک مجموعه خالی می‌سازد.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) متد

معادل سازنده پیش‌فرض.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) متد

یک کپی سطحی از مجموعهٔ تفویض‌کننده انجام می‌دهد.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| o | const MulticastDelegate\& | یک نمونه از کلاس MulticastDelegate برای کپی‌کردن مجموعهٔ تفویض‌کننده‌ها از. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) متد

سازندهٔ جابه‌جایی.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| o | MulticastDelegate\&& | یک نمونه از کلاس MulticastDelegate برای جابه‌جایی مجموعهٔ تفویض‌کننده‌ها از. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) متد

یک نمونه می‌سازد و تفویض‌کنندهٔ مشخص‌شده را به مجموعهٔ تفویض‌کننده‌ها اضافه می‌کند.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | یک تفویض‌کننده برای افزودن به مجموعهٔ تفویض‌کننده‌ها |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) متد

یک نمونه می‌سازد و مقدار مشخص‌شده را به مجموعهٔ تفویض‌کننده‌ها اضافه می‌کند.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار برای افزودن به مجموعهٔ تفویض‌کنندهٔ نمونهٔ تازه ساخته‌شده؛ نوع باید قابل تبدیل به نوع Callback باشد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arg | T | مقداری برای افزودن به مجموعهٔ تفویض‌کننده‌ها |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) متد

یک نمونه می‌سازد و مقدار مشخص‌شده را به مجموعهٔ تفویض‌کننده‌ها اضافه می‌کند.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | مقداری برای افزودن به مجموعهٔ تفویض‌کننده‌ها |

## موارد مرتبط

* Typedef [Callback](../callback/)
* کلاس [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)