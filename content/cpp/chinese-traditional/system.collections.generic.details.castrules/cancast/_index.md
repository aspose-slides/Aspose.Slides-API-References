---
title: CanCast()
second_title: Aspose.Slides for C++ API 參考
description: 檢查轉型可能性。
type: docs
weight: 40
url: /zh-hant/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

當投射後返回非 nullptr 值時為 True，否則為 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

當投射後返回非 nullptr 值時為 True，否則為 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

當投射後返回非 nullptr 值時為 True，否則為 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

永遠傳回 true。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

當投射後返回非 nullptr 值時為 True，否則為 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

永遠傳回 true。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

如果成功完成轉型操作則為 True，否則為 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函式


檢查轉型可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 傳回值

永遠傳回 false。

## 另請參閱

* 結構 [CastType](../casttype/)
* 命名空間 [System::Collections::Generic::Details::CastRules](../)
* 函式庫 [Aspose.Slides](../../)