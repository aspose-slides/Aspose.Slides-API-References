---
title: DynamicCast_noexcept()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 舊的已淘汰轉型。將在未來版本中移除。
type: docs
weight: 2523
url: /zh-hant/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) 函式


舊的已淘汰轉型。將在未來版本中移除。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### 範本參數

| Parameter | Description |
| --- | --- |
| TTo | 目標 Exception 類型。 |
| TFrom | 來源 Exception 類型。 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | 來源指標。 |

### 回傳值

如果允許轉型則返回轉型結果，否則返回 nullptr。

## 備註


對 Exception 物件執行動態轉型。已棄用
:   為了向後相容而保留。請改用 AsCast。

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) 函式


對 [SmartPtr](../smartptr/) 物件執行動態轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### 範本參數

| Parameter | Description |
| --- | --- |
| TTo | 目標指向類型。 |
| TFrom | 來源指向類型。 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 來源指標。 |

### 回傳值

如果允許轉型則返回轉型結果，否則返回 nullptr。

已棄用
:   為了向後相容而保留。請改用 AsCast。

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) 函式


將 Objects 執行動態轉型為 Exception 物件。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### 範本參數

| Parameter | Description |
| --- | --- |
| TTo | 目標 Exception 類型。 |
| TFrom | [Object](../object/) 類型。 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 來源指標。 |

### 回傳值

如果允許轉型則返回轉型結果，否則返回 nullptr。

已棄用
:   為了向後相容而保留。請改用 AsCast。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 類別 [Object](../object/)
* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)