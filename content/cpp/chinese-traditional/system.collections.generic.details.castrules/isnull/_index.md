---
title: IsNull()
second_title: Aspose.Slides for C++ API 參考
description: 檢查所表示的值是否為 nullptr。
type: docs
weight: 27
url: /zh-hant/system.collections.generic.details.castrules/isnull/
---
## System::Collections::Generic::Details::CastRules::IsNull(T) 函式


檢查所表示的值是否為 nullptr。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(T)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 值類型。 |

### 返回值

始終傳回 false。

## System::Collections::Generic::Details::CastRules::IsNull(SharedPtr\<T\>) 函式


檢查所表示的值是否為 nullptr。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(SharedPtr<T> value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 值類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [SharedPtr](../../system/sharedptr/)\<T\> | 必須檢查的值。 |

### 返回值

如果值為 nullptr，則傳回 true，否則傳回 false。

## System::Collections::Generic::Details::CastRules::IsNull(Nullable\<T\>) 函式


檢查所表示的值是否為 nullptr。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(Nullable<T> value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 值類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [Nullable](../../system/nullable/)\<T\> | 必須檢查的值。 |

### 返回值

如果值為 nullptr，則傳回 true，否則傳回 false。

## 另見

* 型別別名 [SharedPtr](../../system/sharedptr/)
* 類別 [Nullable](../../system/nullable/)
* 命名空間 [System::Collections::Generic::Details::CastRules](../)
* 函式庫 [Aspose.Slides](../../)