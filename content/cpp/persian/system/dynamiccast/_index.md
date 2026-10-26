---
title: DynamicCast()
second_title: مرجع API Aspose.Slides برای C++
description: تبدیل دینامیک بر روی اشیای Exception انجام می‌دهد.
type: docs
weight: 2536
url: /fa/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) تابع


یک تبدیل دینامیک بر روی اشیای Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### مقدار بازگشت

Cast result if cast is allowed.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) تابع


یک تبدیل دینامیک بر روی اشیای [SmartPtr](../smartptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### مقدار بازگشت

Cast result if cast is allowed.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::DynamicCast(SmartPtr\<TFrom\>) تابع


مقدار enum بسته شده را با تبدیل خارج می‌کند.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target enum type. |
| TFrom | Source pointee type. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointer to the object to unbox data from. |

### مقدار بازگشت

Unboxed enum value.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::DynamicCast(std::nullptr_t) تابع


یک تبدیل دینامیک بر روی اشیای null انجام می‌دهد.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |

### مقدار بازگشت

nullptr.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::DynamicCast(TFrom\&) تابع


یک تبدیل دینامیک بر روی اشیای غیر اشاره‌گر انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | Source object. |

### مقدار بازگشت

Cast result.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::DynamicCast(SmartPtr\<TFrom\>) تابع


یک تبدیل دینامیک بر روی Objects به اشیای Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### مقدار بازگشت

Cast result if cast is allowed.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::DynamicCast(TFrom) تابع


یک تبدیل دینامیک از IntPtr به اشاره‌گر انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | Source IntPtr value. |

### مقدار بازگشت

Cast result.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## مراجع

* کلاس [SmartPtr](../smartptr/)
* کلاس [Object](../object/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* ساختار [CastResult](../castresult/)
* ساختار [IsSmartPtr](../issmartptr/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)