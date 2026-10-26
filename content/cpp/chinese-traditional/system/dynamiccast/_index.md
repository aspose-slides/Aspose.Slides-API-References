---
title: DynamicCast()
second_title: Aspose.Slides for C++ API 參考文件
description: 對 Exception 物件執行動態轉型。
type: docs
weight: 2536
url: /zh-hant/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) 函式


對 Exception 物件執行動態轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標 Exception 類型。 |
| TFrom | 來源 Exception 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const TFrom\& | 來源指標。 |

### 傳回值

轉型結果（若允許轉型）。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## System::DynamicCast(SmartPtr\<TFrom\> const\&) 函式


對 [SmartPtr](../smartptr/) 物件執行動態轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標指向類型。 |
| TFrom | 來源指向類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 來源指標。 |

### 傳回值

轉型結果（若允許轉型）。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## System::DynamicCast(SmartPtr\<TFrom\>) 函式


透過轉型解除封裝的列舉。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標列舉類型。 |
| TFrom | 來源指向類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 用於解除封裝資料的物件指標。 |

### 傳回值

解除封裝的列舉值。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## System::DynamicCast(std::nullptr_t) 函式


對 null 物件執行動態轉型。

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標指向類型。 |

### 傳回值

nullptr。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## System::DynamicCast(TFrom\&) 函式


對非指標物件執行動態轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標類型。 |
| TFrom | 來源類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | TFrom\& | 來源物件。 |

### 傳回值

轉型結果。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## System::DynamicCast(SmartPtr\<TFrom\>) 函式


對 Objects 執行動態轉型為 Exception 物件。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標 Exception 類型。 |
| TFrom | [Object](../object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 來源指標。 |

### 傳回值

轉型結果（若允許轉型）。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## System::DynamicCast(TFrom) 函式


從 IntPtr 轉型為指標。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標類型。 |
| TFrom | 來源類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | TFrom | 來源 IntPtr 值。 |

### 傳回值

轉型結果。

已棄用
:   為了向後相容而保留。請改用 ExplicitCast。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 類別 [Object](../object/)
* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 結構 [CastResult](../castresult/)
* 結構 [IsSmartPtr](../issmartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)