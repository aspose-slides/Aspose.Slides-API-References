---
title: StaticCast()
second_title: Aspose.Slides for C++ API 參考
description: 對 SmartPtr 物件執行靜態轉換。
type: docs
weight: 2562
url: /zh-hant/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) 函數


對 [SmartPtr](../smartptr/) 物件執行靜態轉換。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | 目標所指類型。 |
| TFrom | 來源所指類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 來源指標。 |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(WeakPtr\<TFrom\> const\&) 函數


對 [WeakPtr](../weakptr/) 物件執行靜態轉換。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | 目標所指類型。 |
| TFrom | 來源所指類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | 來源指標。 |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(std::nullptr_t) 函數


對 null 物件執行靜態轉換。

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | 目標所指類型。 |

### Return Value

nullptr.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(TFrom) 函數


針對算術類型的特化。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) 函數


處理從 [String](../string/) 到 [String](../string/) 的轉換。

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) 函數


針對算術類型的特化。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) 函數


對非指標物件執行靜態轉換。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | 目標類型。 |
| TFrom | 來源類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | 來源物件。 |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(const TFrom\&) 函數


對 Exception 物件執行靜態轉換。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | 目標 Exception 類型。 |
| TFrom | 來源 Exception 類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | 來源指標。 |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::StaticCast(SmartPtr\<TFrom\>) 函數


對 Objects 執行靜態轉換為 Exception 物件。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | 目標 Exception 類型。 |
| TFrom | [Object](../object/) 類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 來源指標。 |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## See Also

* 類別 [SmartPtr](../smartptr/)
* 類別 [WeakPtr](../weakptr/)
* 類別 [String](../string/)
* 類別 [Object](../object/)
* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 結構 [CastResult](../castresult/)
* 結構 [IsSmartPtr](../issmartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)