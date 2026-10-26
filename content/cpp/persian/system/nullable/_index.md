---
title: Nullable
second_title: Aspose.Slides برای C++ مرجع API
description: اعلان پیش‌تعریف.
type: docs
weight: 1106
url: /fa/system/nullable/
---
## کلاس Nullable

Forward declaration.

```cpp
template<typename T>class Nullable
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار پایه که توسط کلاس [Nullable](./) گسترش می‌یابد |

## متدها

| Method | Description |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری برابر با مقداری است که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود. |
| **bool** [get_HasValue](./get_hasvalue/)() const | تعیین می‌کند که آیا شیء جاری هر مقداری را نمایان می‌کند یا خیر. |
| T [get_Value](./get_value/)() const | یک نسخه از مقدار نمایان‌شده توسط شیء جاری را باز می‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | کد هش برای شیء جاری را باز می‌گرداند. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | اگر مقدار نمایان‌شده توسط شیء جاری null باشد، مقدار مشخص‌شده را باز می‌گرداند؛ در غیر این صورت مقدار شیء جاری را برمی‌گرداند. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | تعیین می‌کند که آیا شیء جاری مقدار null دارد. |
|  [Nullable](./nullable/)() | نمونه‌ای می‌سازد که مقدار null را نمایان می‌کند. |
|  [Nullable](./nullable/)(std::nullptr_t) | نمونه‌ای می‌سازد که null را نمایان می‌کند. |
|  [Nullable](./nullable/)(const T1\&) | نمونه‌ای از کلاس [Nullable](./) می‌سازد که مقدار مشخص‌شده را (در صورت لزوم) به نوع پایه T تبدیل می‌کند. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | نمونه‌ای می‌سازد که مقداری را که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود، نشان می‌دهد. شیء nullable مشخص‌شده ممکن است مقدار با نوع متفاوت از نوع پایهٔ نمونه ساخت‌شده داشته باشد؛ در این صورت مقدار نمایان‌شده به نوع T تبدیل می‌شود. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | تابع کمکی برای بررسی اینکه آیا این و **other** هر دو null نیستند و در این صورت یک لامبدا را صدا می‌زند. در implementationها استفاده می‌شود. |
|  [operator const T &](./operator_const_t__and/)() const | یک مرجع ثابت به مقداری که توسط شیء جاری نمایان می‌شود باز می‌گرداند. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری null نیست. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری برابر با مقدار مشخص‌شده نیست. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری برابر با مقداری که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود، نیست. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | [operator&=()](./operator_and_equal/) را بر مقدار نمایان‌شده توسط شیء جاری با استفاده از مقدار مشخص‌شده به عنوان آرگومان سمت راست اعمال می‌کند. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | یک نمونه ساخته‌شده به‌طور پیش‌فرض از کلاس Nullable<T> را باز می‌گرداند. |
| auto [operator+](./operator_plus/)(const T1\&) const | مقادیر nullable و non-nullable را جمع می‌کند. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | مقادیر nullable را جمع می‌کند. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | شیء جاری را بازنشانی می‌کند تا مقدار null را نمایان کند. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | [operator+=()](./operator_plus_equal/) را بر مقدار نمایان‌شده توسط شیء جاری با استفاده از مقدار مشخص‌شده به عنوان آرگومان سمت راست اعمال می‌کند. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | [operator+=()](./operator_plus_equal/) را بر مقدار نمایان‌شده توسط شیء جاری با استفاده از مقداری که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود، به عنوان آرگومان سمت راست اعمال می‌کند. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | مقادیر nullable و null-pointed را از هم کم می‌کند. |
| auto [operator-](./operator_minus/)(const T1\&) const | مقادیر nullable و non-nullable را از هم کم می‌کند. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | مقادیر nullable را از هم کم می‌کند. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | نمونه‌ای از کلاس [Nullable](./) برمی‌گرداند که مقدار null را نمایان می‌کند. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | [operator-=()](./operator_minus_equal/) را بر مقدار نمایان‌شده توسط شیء جاری با استفاده از مقدار مشخص‌شده به عنوان آرگومان سمت راست اعمال می‌کند. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | [operator-=()](./operator_minus_equal/) را بر مقدار نمایان‌شده توسط شیء جاری با استفاده از مقداری که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود، به عنوان آرگومان سمت راست اعمال می‌کند. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | همیشه false برمی‌گرداند. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator<()](./operator_less/) بر این مقادیر، کمتر از مقدار مشخص‌شده است. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator<()](./operator_less/) بر این مقادیر، کمتر از مقداری است که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | همیشه false برمی‌گرداند. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator<=()](./operator_less_equal/) بر این مقادیر، کمتر یا مساوی مقدار مشخص‌شده است. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator<=()](./operator_less_equal/) بر این مقادیر، کمتر یا مساوی مقداری است که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | مقدار null را به شیء جاری اختصاص می‌دهد. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | مقدار نمایان‌شده فعلی شیء را با مقدار مشخص‌شده جایگزین می‌کند. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | مقدار نمایان‌شده فعلی شیء را با مقدار مشخص‌شده جایگزین می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری null است. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری برابر با مقدار مشخص‌شده است. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری برابر با مقداری است که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | همیشه false برمی‌گرداند. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator>()](./operator_greater/) بر این مقادیر، بزرگتر از مقدار مشخص‌شده است. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator>()](./operator_greater/) بر این مقادیر، بزرگتر از مقداری است که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | همیشه false برمی‌گرداند. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator>=()](./operator_greater_equal/) بر این مقادیر، بزرگتر یا مساوی مقدار نمایان‌شده توسط شیء مشخص‌شده است. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری با اعمال [operator>=()](./operator_greater_equal/) بر این مقادیر، بزرگتر یا مساوی مقداری است که توسط شیء [Nullable](./) مشخص‌شده نمایان می‌شود. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | [operator|=()](./operator_or_equal/) را بر مقدار نمایان‌شده توسط شیء جاری با استفاده از مقدار مشخص‌شده به عنوان آرگومان سمت راست اعمال می‌کند. |
| void [reset](./reset/)() | مقدار نمایان‌شده فعلی را به null تنظیم می‌کند. |
| void [set_Value](./set_value/)(const T\&) | یک مقدار جدید را به شیء nullable اختصاص می‌دهد. |
| [String](../string/) [ToString](./tostring/)() const | مقدار نمایان‌شده توسط شیء جاری را به رشته تبدیل می‌کند. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | یک نام مستعار برای نوع مقدار نمایان‌شده توسط این کلاس. |

## نکات

نمایش یک مقدار از نوع مشخص‌شده که می‌تواند null اختصاص یابد. این نوع باید بر روی پشته تخصیص داده شود و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)