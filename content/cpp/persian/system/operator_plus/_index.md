---
title: operator+()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از کلاس Decimal را برمی‌گرداند که نمایانگر مقداری است که مجموع مقدار مشخص‌شده و مقدار نمایان‌شده توسط شی Decimal مشخص‌شده می‌باشد.
type: docs
weight: 2185
url: /fa/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) تابع

یک نمونه جدید از کلاس [Decimal](../decimal/) را برمی‌گرداند که مقداری را نشان می‌دهد که مجموع مقدار مشخص‌شده و مقداری که توسط شیء [Decimal](../decimal/) مشخص‌شده نمایانده می‌شود.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const T\& | اولین جمع‌کننده |
| d | const [Decimal](../decimal/)\& | مرجع ثابت به شیء [Decimal](../decimal/) که نمایانگر جمع‌کننده دوم است |

### مقدار بازگشت

یک نمونه جدید از کلاس [Decimal](../decimal/) که مقداری را نشان می‌دهد که مجموع **x** و مقداری که توسط **d** نمایانده می‌شود.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) تابع

تمام کال‌بیك‌ها را از نمایندهٔ سمت راست به انتهای فهرست کال‌بیك‌های نمایندهٔ سمت چپ متصل می‌کند.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | نماینده‌ای که کال‌بیك‌ها به آن اضافه می‌شوند. |
| rhv | MulticastDelegate\<T\> | نماینده‌ای که کال‌بیك‌های آن اضافه می‌شوند. |

### مقدار بازگشت

یک نماینده را برمی‌گرداند که شامل کال‌بیك‌های مقدار سمت چپ و سپس کال‌بیك‌های سمت راست است.

## System::operator+(const T1\&, const Nullable\<T2\>\&) تابع

مقادیری که قابل‌نول نیستند و قابل‌نول هستند را جمع می‌کند.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عملوند چپ. |
| T2 | نوع عملوند راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| some | const T1\& | عملوند چپ. |
| other | const [Nullable](../nullable/)\<T2\>\& | عملوند راست. |

### مقدار بازگشت

نتیجهٔ جمع.

## System::operator+(T\&, const String\&) تابع

[String](../string/) ادغام.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [String](../string/) نوع literal. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | T\& | literal برای الحاق به رشته. |
| right | const [String](../string/)\& | [String](../string/) برای الحاق. |

### مقدار بازگشت

رشتهٔ الحاق‌شده.

## System::operator+(T\&, const String\&) تابع

[String](../string/) ادغام.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [String](../string/) نوع pointer. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer برای الحاق به رشته. |
| right | const [String](../string/)\& | [String](../string/) برای الحاق. |

### مقدار بازگشت

رشتهٔ الحاق‌شده.

## System::operator+(const char_t, const String\&) تابع

[String](../string/) ادغام.

```cpp
String System::operator+(const char_t left, const String &right)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | const char_t | کاراکتر برای الحاق به رشته. |
| right | const [String](../string/)\& | [String](../string/) برای الحاق. |

### مقدار بازگشت

رشتهٔ الحاق‌شده.

## موارد مرتبط

* کلاس [Decimal](../decimal/)
* کلاس [Nullable](../nullable/)
* کلاس [String](../string/)
* ساختار [IsStringLiteral](../isstringliteral/)
* ساختار [IsStringPointer](../isstringpointer/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)