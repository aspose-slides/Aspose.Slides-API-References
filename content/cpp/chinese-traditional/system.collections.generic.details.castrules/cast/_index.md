---
title: Cast()
second_title: Aspose.Slides for C++ API 參考手冊
description: 將來源型別轉換為結果型別。當來源型別與結果型別相同時使用。
type: docs
weight: 14
url: /zh-hant/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當來源型別與結果型別相同時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當來源型別可靜態轉換為結果型別時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當型別不同且來源型別無法靜態轉換為結果型別時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當來源型別被裝箱為 [Nullable](../../system/nullable/) 類別實例時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當來源型別從 [Nullable](../../system/nullable/) 類別實例解除裝箱時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當來源型別被裝箱為 [Object](../../system/object/) 類別實例時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當來源型別從 [Object](../../system/object/) 類別實例解除裝箱時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) 函式


將來源型別轉換為結果型別。當轉型無效或轉換為顯式時使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 回傳值

The cast result.

## 另請參閱

* Struct [CastType](../casttype/)
* 命名空間 [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)