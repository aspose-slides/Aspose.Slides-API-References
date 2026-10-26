---
title: StaticCastArray()
second_title: Aspose.Slides برای مرجع API C++
description: عناصر آرایهٔ مشخص‌شده را به نوع متفاوت تبدیل می‌کند. بازنویسی برای حالاتی که From یک شیء SmartPtr است.
type: docs
weight: 2978
url: /fa/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) تابع


تبدیل عناصر آرایهٔ مشخص‌شده به نوع متفاوت را انجام می‌دهد. بازنویسی برای مواردی که From یک شیء [SmartPtr](../smartptr/) است.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| To | نوعی که عناصر آرایهٔ مشخص‌شده به آن تبدیل می‌شوند |
| From | نوع عناصری که در آرایهٔ مورد نظر برای تبدیل وجود دارد |

### آرگومان‌ها

| پارامتر | Type | توضیح |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | اشاره‌گر اشتراکی به آرایه‌ای که شامل عناصری برای تبدیل است |

### مقدار بازگشت

یک اشاره‌گر به آرایهٔ جدیدی که شامل عناصری از نوع **To** برابر با عناصر **from** است

منسوخ شده
:   برای سازگاری نسخه‌های قبلی اضافه شده است. به جای آن از ExplicitCast استفاده کنید.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) تابع


تبدیل عناصر آرایهٔ مشخص‌شده به نوع متفاوت را انجام می‌دهد. بازنویسی برای مواردی که From قابلیت Boxable باشد و To یک [Object](../object/)[] است.

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| To | نوعی که عناصر آرایهٔ مشخص‌شده به آن تبدیل می‌شوند |
| From | نوع عناصری که در آرایهٔ مورد نظر برای تبدیل وجود دارد |

### آرگومان‌ها

| پارامتر | Type | توضیح |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | اشاره‌گر اشتراکی به آرایه‌ای که شامل عناصری برای تبدیل است |

### مقدار بازگشت

یک اشاره‌گر به آرایهٔ جدیدی که شامل عناصری از نوع **To** برابر با عناصر **from** است

منسوخ شده
:   برای سازگاری نسخه‌های قبلی اضافه شده است. به جای آن از ExplicitCast استفاده کنید.

## مراجعه کنید

* تعریف‌نوع [SharedPtr](../sharedptr/)
* کلاس [Array](../array/)
* کلاس [Object](../object/)
* ساختار [IsSmartPtr](../issmartptr/)
* ساختار [IsBoxable](../isboxable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)