---
title: StaticCast_noexcept()
second_title: Aspose.Slides for C++ API 參考
description: 對 SmartPtr 物件執行靜態轉型。
type: docs
weight: 2549
url: /zh-hant/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) 函式


對 [SmartPtr](../smartptr/) 物件執行靜態轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
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

### 返回值

如果允許轉型則返回轉型結果，否則返回 nullptr。

已棄用
:   為了向後相容性保留。請使用 AsCast 取代。

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) 函式


對 [WeakPtr](../weakptr/) 物件執行靜態轉型。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TTo | 目標指向類型。 |
| TFrom | 來源指向類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | 來源指標。 |

### 返回值

如果允許轉型則返回轉型結果，否則返回 nullptr。

已棄用
:   為了向後相容性保留。請使用 AsCast 取代。

## System::StaticCast_noexcept(const TFrom\&) 函式


對 Exception 物件執行靜態轉型。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
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

### 返回值

如果允許轉型則返回轉型結果，否則返回 nullptr。

已棄用
:   為了向後相容性保留。請使用 AsCast 取代。

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) 函式


對 Objects 進行靜態轉型為 Exception 物件。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
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

### 返回值

如果允許轉型則返回轉型結果，否則返回 nullptr。

已棄用
:   為了向後相容性保留。請使用 AsCast 取代。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 類別 [WeakPtr](../weakptr/)
* 類別 [Object](../object/)
* 結構 [IsExceptionWrapper](../isexceptionwrapper/)
* 結構 [CastResult](../castresult/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)