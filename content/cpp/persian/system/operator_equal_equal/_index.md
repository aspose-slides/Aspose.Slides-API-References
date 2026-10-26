---
title: operator==()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 2042
url: /fa/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) تابع




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) تابع




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) تابع




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) تابع


تشخیص می‌دهد آیا شیء [Nullable](../nullable/) مشخص‌شده مقدار برابر با null دارد یا نه.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | std::nullptr_t | یک ارجاع ثابت به شیء [Nullable](../nullable/) برای آزمون |

### مقدار بازگشت

True اگر شیء مشخص‌شده مقدار null باشد، در غیر این صورت false

## System::operator==(const T1\&, const Nullable\<T2\>\&) تابع


تشخیص می‌دهد آیا مقدار مشخص‌شده برابر با مقدار نمایانگر توسط شیء [Nullable](../nullable/) مشخص‌شده است با اعمال [operator==()](./) بر این مقادیر.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقدار مقایسه‌کننده اول |
| T2 | نوع پایهٔ شیء [Nullable](../nullable/) که مقدار مقایسه‌کننده دوم را نمایان می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| some | const T1\& | یک ارجاع ثابت به مقداری که به عنوان مقایسه‌کنندهٔ اول استفاده می‌شود |
| other | const [Nullable](../nullable/)\<T2\>\& | یک ارجاع ثابت به شیء [Nullable](../nullable/) که مقدار نمایان‌شدهٔ آن به عنوان مقایسه‌کنندهٔ دوم استفاده می‌شود |

### مقدار بازگشت

True اگر مقایسه‌کننده‌ها برابر باشند، در غیر این صورت false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) تابع


مقایسهٔ مساوی دو هوشمند اشاره‌گر.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع شیء اشاره‌شدهٔ نشانگر اول. |
| Y | نوع شیء اشاره‌شدهٔ نشانگر دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | اولین اشاره‌گری که مقایسه می‌شود. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | دومین اشاره‌گری که مقایسه می‌شود. |

### مقدار بازگشت

True اگر اشاره‌گرها برابر باشند، در غیر این صورت false

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) تابع


بررسی می‌کند آیا هوشمند اشاره‌گر null است.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع شیء اشاره‌شدهٔ اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | std::nullptr_t | اشاره‌گری برای بررسی. |

### مقدار بازگشت

True اگر اشاره‌گر null باشد، در غیر این صورت false

## System::operator==(const SmartPtr\<X\>\&, const Y *) تابع


مقایسهٔ مساوی هوشمند اشاره‌گر با اشاره‌گر ساده (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع هوشمند اشاره‌گر. |
| Y | نوع اشاره‌گر ساده. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | هوشمند اشاره‌گر برای مقایسه (چپ). |
| y | const Y * | اشاره‌گر ساده برای مقایسه (راست). |

### مقدار بازگشت

True اگر اشاره‌گرها برابر باشند، در غیر این صورت false

## System::operator==(const X *, const SmartPtr\<Y\>\&) تابع


مقایسهٔ مساوی هوشمند اشاره‌گر با اشاره‌گر ساده (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| X | نوع اشاره‌گر ساده. |
| Y | نوع هوشمند اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const X * | اشاره‌گر ساده برای مقایسه (راست). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | هوشمند اشاره‌گر برای مقایسه (چپ). |

### مقدار بازگشت

True اگر اشاره‌گرها برابر باشند، در غیر این صورت false

## System::operator==(T const\&, std::nullptr_t) تابع


بررسی می‌کند آیا شیء نوع مقدار (ساختار ترجمه‌شدهٔ C# و ...) null است.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | T const\& | [Object](../object/) برای بررسی. |

### مقدار بازگشت

True اگر شیء null باشد، در غیر این صورت false

## System::operator==(std::nullptr_t, T const\&) تابع


بررسی می‌کند آیا شیء نوع مقدار (ساختار ترجمه‌شدهٔ C# و ...) null است.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) برای بررسی. |

### مقدار بازگشت

True اگر شیء null باشد، در غیر این صورت false

## System::operator==(Chars\&, const String\&) تابع


مقایسهٔ [String](../string/).

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Chars | نوع حرفی [String](../string/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | Chars\& | مقدار حرفی [String](../string/) برای مقایسه. |
| right | const [String](../string/)\& | [String](../string/) برای مقایسه. |

### مقدار بازگشت

true اگر رشته‌ها برابر باشند، در غیر این صورت false

## System::operator==(T\&, const String\&) تابع


مقایسهٔ [String](../string/).

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
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

true اگر رشته‌ها برابر باشند، در غیر این صورت false

## System::operator==(const SharedPtr\<Object\>\&, const String\&) تابع


مقایسهٔ [Object](../object/) و رشته.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) برای تبدیل به رشته و مقایسه. |
| right | const [String](../string/)\& | [String](../string/) برای مقایسه. |

### مقدار بازگشت

true اگر نمایش رشته‌ای شیء برابر با رشته باشد، در غیر این صورت false

## System::operator==(std::nullptr_t, const String\&) تابع


بررسی می‌کند آیا رشته null است.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) برای بررسی. |

### مقدار بازگشت

true اگر رشته null باشد، در غیر این صورت false

## System::operator==(std::nullptr_t, TimeSpan) تابع




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) تابع


تشخیص می‌دهد آیا URIهای نمایان‌شده توسط شیء فعلی و شیء مشخص‌شده برابر هستند.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | اولین شیء [Uri](../uri/) برای مقایسه |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | دومین شیء [Uri](../uri/) برای مقایسه |

### مقدار بازگشت

True اگر URIها برابر باشند، در غیر این صورت false

## موارد مرتبط

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)