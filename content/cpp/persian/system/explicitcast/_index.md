---
title: ExplicitCast()
second_title: مرجع API Aspose.Slides برای C++
description: نوع منبع را با استفاده از تبدیل صریح به نوع نتیجه تبدیل می‌کند. هنگامی استفاده می‌شود که نوع منبع و نوع نتیجه یکسان باشند.
type: docs
weight: 2627
url: /fa/system/explicitcast/
---
## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. هنگامی استفاده می‌شود که نوع منبع و نوع نتیجه یکسان باشند.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. هنگامی استفاده می‌شود که نیاز به تبدیل ساده شبیه سازنده باشد.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای بسته‌بندهای استثنا استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای تبدیل شیء به استثنا استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. زمانی که منبع و نتیجه هر دو اشاره‌گرهای هوشمند هستند (بدون SmartPtr<...> صریح در نوع نتیجه) استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(Source) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. هنگام تبدیل اشاره‌گر خام به اشاره‌گر هوشمند استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | Source | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. زمانی که منبع و نتیجه هر دو اشاره‌گرهای هوشمند هستند (با SmartPtr<...> صریح در نوع نتیجه) استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای باز کردن شیء به nullable استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای بسته‌بندی nullable استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای باز کردن nullable شیء استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای بسته‌بندی enum استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای کپی‌کردن انواع مقدار به heap زمانی که نوع مقدار باید به عنوان اشاره‌گر هوشمند ارجاع داده شود (در genericهایی که با نوع اینترفیس محدود شده‌اند اما با ساختاری که این اینترفیس را پیاده‌سازی می‌کند تخصصی شده‌اند) استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای دریافت اینترفیس‌ها از انواع مقدار استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای بسته‌بندی عمومی استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای بسته‌بندی [System::String](../string/) استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای باز کردن اینترفیس‌ها استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای باز کردن عمومی استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای تبدیل nullptr استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::ExplicitCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از تبدیل صریح تبدیل می‌کند. برای تبدیل بین آرایه‌ها استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## موارد مرتبط

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)