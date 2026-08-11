---
title: Delegate()
second_title: مرجع API Aspose.Slides برای C++
description: سازنده پیش‌فرض. شیء delegate را می‌سازد که به هیچ‌چیز اشاره ندارد.
type: docs
weight: 1
url: /fa/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() متد

سازنده پیش‌فرض. شیء delegate را می‌سازد که به هیچ چیزی اشاره ندارد.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) متد




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) متد

سازنده کپی انتقالی. مالکیت موجودیتی که توسط delegate مشخص‌شده اشاره می‌شود را می‌گیرد.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| o | Delegate\&& | شیء Delegate برای انتقال موجودیتی که به آن اشاره شده است |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) متد

سازنده. شیء delegate را از اشاره‌گر مشخص‌شده به تابع آزاد یا متد ایستاتیک می‌سازد.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| The | نوع اشاره‌گر به تابع یا متد ایستاتیک که توسط سازنده به‌عنوان آرگومان پذیرفته می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| function | T | اشاره‌گر به تابع یا متد ایستاتیکی که توسط نمونهٔ تازه ساختهٔ Delegate اشاره خواهد شد |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) متد

سازنده. شیء delegate را از اشاره‌گر مشخص‌شده به شیء تابعی که توسط std::bind() تولید شده است می‌سازد.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| The | نوع شیء تابعی که توسط std::bind() تولید شده و توسط سازنده به‌عنوان آرگومان پذیرفته می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| function | T | اشاره‌گری به «عبارت bind» - یک اشاره‌گر به تابع که توسط std::bind() تولید شده است - که توسط نمونهٔ تازه ساختهٔ Delegate اشاره خواهد شد |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) متد

سازنده. شیء delegate را از شیء تابعی که مشخص شده است می‌سازد.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء تابعی که توسط سازنده به‌عنوان آرگومان پذیرفته می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functor_tag | int | مقدار عددی ساختگی؛ این آرگومان برای رفع ابهام استفاده می‌شود |
| functor | T\& | شیء تابعی که delegate تازه ساخته‌شده به آن اشاره خواهد کرد |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) متد

سازندهٔ انتقالی. شیء delegate را از شیء تابعی که مشخص شده است می‌سازد.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء تابعی که توسط سازنده به‌عنوان آرگومان پذیرفته می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| functor_tag | long | مقدار عددی ساختگی؛ این آرگومان برای رفع ابهام استفاده می‌شود |
| functor | T\&& | شیء تابعی که delegate تازه ساخته‌شده به آن اشاره خواهد کرد |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) متد

سازنده. شیء delegate را می‌سازد که به متد غیر ایستاتیک مشخص‌شدهٔ شیء موردنظر اشاره می‌کند.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| MemberType | نوع متد غیر ایستاتیکی که سازنده به‌عنوان آرگومان می‌پذیرد |
| ClassType | نوع شیئی که سازنده به‌عنوان آرگومان می‌پذیرد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| member | MemberType ClassType::* | اشاره‌گری به متد غیر ایستاتیک که delegate تازه ساخته‌شده به آن اشاره خواهد کرد |
| obj | ClassType * | اشاره‌گری به شیئی که متد عضو آن توسط delegate تازه ساخته‌شده هدف خواهد شد |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) متد

سازنده. شیء delegate را می‌سازد که به متد غیر ایستاتیک مشخص‌شدهٔ شیء موردنظر اشاره می‌کند.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| MemberType | نوع متد غیر ایستاتیکی که سازنده به‌عنوان آرگومان می‌پذیرد |
| ClassType | نوع شیئی که سازنده به‌عنوان آرگومان می‌پذیرد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| member | MemberType MemberClass::* | اشاره‌گری به متد غیر ایستاتیک که delegate تازه ساخته‌شده به آن اشاره خواهد کرد |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | یک shared pointer به شیئی که متد عضو آن توسط delegate تازه ساخته‌شده هدف خواهد شد |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) متد

شیء delegate را می‌سازد که به یک شیء تابع std::function اشاره می‌کند.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| R | نوع بازگشت شیء تابعی که سازنده به‌عنوان آرگومان می‌پذیرد |
| Args | فهرست آرگومان‌های شیء تابعی که سازنده به‌عنوان آرگومان می‌پذیرد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| f | std::function\<R(Args...)> | شیء تابعی که توسط نمونهٔ تازه ساختهٔ delegate هدف خواهد شد |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)