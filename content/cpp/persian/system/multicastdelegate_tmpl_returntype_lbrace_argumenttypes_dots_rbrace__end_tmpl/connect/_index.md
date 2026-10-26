---
title: connect()
second_title: Aspose.Slides برای C++ مستندات API
description: Delegate مشخص‌شده را به مجموعه اضافه می‌کند.
type: docs
weight: 144
url: /fa/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) متد

Delegate مشخص‌شده را به مجموعه اضافه می‌کند.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegate برای افزودن به مجموعه |

### مقدار بازگشت

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) متد

Object تابع مشخص‌شده را به مجموعه delegate اضافه می‌کند. قبل از افزودن به مجموعه، object تابع به نوع Callback delegate تبدیل می‌شود.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| R | نوع بازگشتی object تابع برای افزودن به مجموعه |
| Args | لیست آرگومان‌های object تابع برای افزودن به مجموعه |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Object تابع برای افزودن به مجموعه |

### مقدار بازگشت

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) متد

Object MulticastDelegate مشخص‌شده را به مجموعه delegate اضافه می‌کند.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | یک نمونه از کلاس MulticastDelegate برای افزودن به مجموعه delegate |

### مقدار بازگشت

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) متد

متد غیر استاتیک مشخص‌شده از شیء مشخص‌شده را به مجموعه delegate اضافه می‌کند.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| MemberType | نوع متد غیر استاتیک که باید به مجموعه delegate اضافه شود |
| ClassType | نوع شیئی که متد آن باید به مجموعه اضافه شود |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| member | MemberType ClassType::* | یک اشاره‌گر به متد غیر استاتیک شیء مشخص‌شده |
| obj | ClassType * | یک اشاره‌گر به متد عضو شیء که باید به مجموعه delegate اضافه شود |

### مقدار بازگشت

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) متد

متد غیر استاتیک مشخص‌شده از شیء مشخص‌شده را به مجموعه delegate اضافه می‌کند.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| MemberType | نوع متد غیر استاتیک که باید به مجموعه delegate اضافه شود |
| ClassType | نوع شیئی که متد آن باید به مجموعه delegate اضافه شود |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| member | MemberType ClassType::* | یک اشاره‌گر به متد غیر استاتیک شیء مشخص‌شده |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | یک SharedPtr مشترک به متد عضو شیء که باید به مجموعه delegate اضافه شود |

### مقدار بازگشت

A reference to the self

## موارد مرتبط

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)