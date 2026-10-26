---
title: AsCast()
second_title: Aspose.Slides برای مرجع API C++
description: نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. زمانی که به تبدیل ساده‌ای شبیه سازنده نیاز باشد، استفاده می‌شود.
type: docs
weight: 2640
url: /fa/system/ascast/
---
## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. زمانی که نیاز به تبدیل ساده‌ای شبیه سازنده باشد، استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. زمانی که نوع منبع و نوع نتیجه یکسان باشند، استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای بسته‌بندهای استثنا استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای تبدیل شی به استثنا استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. زمانی که منبع و نتیجه هر دو اشاره‌گرهای هوشمند باشند، استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل. Returns nullptr if no conversion available.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. زمانی که منبع و نتیجه هر دو اشاره‌گرهای هوشمند باشند (با SmartPtr<...> صریح در نوع نتیجه)، استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل. Returns nullptr if no conversion available.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای استخراج شی به مقدار nullable استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل. Returns empty nullable if no conversion available.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. استخراج نامعتبر به نوع غیر شی.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

همواره null باز می‌گردد.

## System::AsCast(const Source\&) تابع

استخراج نامعتبر به نوع غیر شی.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

همواره null باز می‌گردد.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای بسته‌بندی شی nullable استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای بسته‌بندی شی عمومی استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای بسته‌بندی شی عمومی استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای استخراج رشته استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای حالت‌گذاری nullptr استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل.

## System::AsCast(const Source\&) تابع

نوع منبع را به نوع نتیجه با استفاده از عملگر تبدیل 'as' تبدیل می‌کند. برای تبدیل بین آرایه‌ها استفاده می‌شود.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) برای تبدیل. |

### مقدار بازگشت

نتیجه تبدیل. Returns nullptr if no conversion for any array member is available.

## See Also

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)