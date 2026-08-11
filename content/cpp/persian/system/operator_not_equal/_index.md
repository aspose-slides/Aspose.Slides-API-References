---
title: operator!=()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 2055
url: /fa/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) تابع




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) تابع




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) تابع




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) تابع


تعیین می‌کند که آیا شیء [Nullable](../nullable/) مشخص شده مقداری دارد که برابر با null نیست.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | std::nullptr_t | یک مرجع ثابت به شیء [Nullable](../nullable/) برای آزمایش |

### مقدار بازگشت

درست اگر شیء مشخص شده مقدار غیر null را نمایانگر باشد، در غیر این صورت نادرست

## System::operator!=(const T1\&, const Nullable\<T2\>\&) تابع


تعیین می‌کند که آیا مقدار مشخص شده برابر با مقداری که توسط شیء [Nullable](../nullable/) مشخص شده نمایانگر است نیست، با اعمال [operator!=()](./) بر این مقادیر.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع اولین مقدار مقایسه‌ای |
| T2 | نوع پایهٔ شیء [Nullable](../nullable/) که مقدار دوم مقایسه‌ای را نمایانگر است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| some | const T1\& | یک مرجع ثابت به مقداری که به عنوان اولین مقایسه‌کننده استفاده می‌شود |
| other | const [Nullable](../nullable/)\<T2\>\& | یک مرجع ثابت به شیء [Nullable](../nullable/) که مقدار نمایانگرش به عنوان دومین مقایسه‌کننده استفاده می‌شود |

### مقدار بازگشت

درست اگر مقایسه‌کننده‌ها برابر نباشند، در غیر این صورت نادرست

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) تابع


مقایسه نابرابری دو اشاره‌گر هوشمند.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع مؤلفه‌دار اولین اشاره‌گر. |
| Y | نوع مؤلفه‌دار دومین اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | اولین اشاره‌گر برای مقایسه. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | دومین اشاره‌گر برای مقایسه. |

### مقدار بازگشت

نادرست اگر اشاره‌گرها مطابق باشند، در غیر این صورت درست.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) تابع


بررسی می‌کند که آیا اشاره‌گر هوشمند نال نیست.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع مؤلفه‌دار اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | اشاره‌گر برای بررسی. |

### مقدار بازگشت

نادرست اگر اشاره‌گر نال باشد، در غیر این صورت درست.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) تابع


بررسی می‌کند که آیا اشاره‌گر هوشمند نال نیست.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع مؤلفه‌دار اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | std::nullptr_t | اشاره‌گر برای بررسی. |

### مقدار بازگشت

نادرست اگر اشاره‌گر نال باشد، در غیر این صورت درست.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) تابع


مقایسه نابرابری اشاره‌گر هوشمند با اشاره‌گر ساده (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع اشاره‌گر هوشمند. |
| Y | نوع اشاره‌گر ساده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | اشاره‌گر هوشمند برای مقایسه (چپ). |
| y | const Y * | اشاره‌گر برای مقایسه (راست). |

### مقدار بازگشت

نادرست اگر اشاره‌گرها مطابق باشند، در غیر این صورت درست.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) تابع


مقایسه برابری اشاره‌گر هوشمند با اشاره‌گر ساده (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع اشاره‌گر ساده. |
| Y | نوع اشاره‌گر هوشمند. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const X * | اشاره‌گر برای مقایسه (راست). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | اشاره‌گر هوشمند برای مقایسه (چپ). |

### مقدار بازگشت

نادرست اگر اشاره‌گرها مطابق باشند، در غیر این صورت درست.

## System::operator!=(Chars\&, const String\&) تابع


مقایسه [String](../string/).

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Chars | نوع literal [String](../string/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | Chars\& | literal [String](../string/) برای مقایسه. |
| right | const [String](../string/)\& | [String](../string/) برای مقایسه. |

### مقدار بازگشت

نادرست اگر رشته‌ها برابر باشند، در غیر این صورت درست.

## System::operator!=(T\&, const String\&) تابع


مقایسه [String](../string/).

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشاره‌گر [String](../string/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | T\& | اشاره‌گر [String](../string/) برای مقایسه. |
| right | const [String](../string/)\& | [String](../string/) برای مقایسه. |

### مقدار بازگشت

نادرست اگر رشته‌ها برابر باشند، در غیر این صورت درست.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) تابع


مقایسه [Object](../object/) و رشته.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) برای تبدیل به رشته و مقایسه. |
| right | const [String](../string/)\& | [String](../string/) برای مقایسه. |

### مقدار بازگشت

نادرست اگر نمایش رشته‌ای شیء برابر با رشته باشد، در غیر این صورت درست.

## System::operator!=(std::nullptr_t, const String\&) تابع


بررسی می‌کند که آیا رشته نال است.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) برای بررسی. |

### مقدار بازگشت

نادرست اگر رشته نال باشد، در غیر این صورت درست.

## System::operator!=(std::nullptr_t, TimeSpan) تابع




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) تابع


تعیین می‌کند که آیا URIهای نمایانده‌شده توسط اشیاء فعلی و مشخص شده برابر نیستند.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | اولین شیء [Uri](../uri/) برای مقایسه |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | دومین شیء [Uri](../uri/) برای مقایسه |

### مقدار بازگشت

درست اگر URIها برابر نباشند، در غیر این صورت نادرست

## مراجع

* تعریف نوع [SharedPtr](../sharedptr/)
* کلاس [ArraySegment](../arraysegment/)
* کلاس [DateTime](../datetime/)
* کلاس [DateTimeOffset](../datetimeoffset/)
* کلاس [Nullable](../nullable/)
* کلاس [SmartPtr](../smartptr/)
* کلاس [Object](../object/)
* کلاس [String](../string/)
* کلاس [TimeSpan](../timespan/)
* کلاس [Uri](../uri/)
* ساختار [IsNullable](../isnullable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)