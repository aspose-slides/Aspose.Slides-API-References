---
title: AsCast()
second_title: Aspose.Slides for C++ API 參考
description: 使用 'as' 運算子將來源型別轉換為結果型別。當需要簡單的建構子式轉型時使用。
type: docs
weight: 2640
url: /zh-hant/system/ascast/
---
## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於需要簡單建構子式轉型的情況。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於來源與結果型別相同的情況。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於例外包裝器。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。若無可用的轉換則傳回 nullptr。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於將物件轉型為例外。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。若無可用的轉換則傳回 nullptr。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於來源與結果皆為智慧指標的情況。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。若無可用的轉換則傳回 nullptr。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於來源與結果皆為智慧指標（結果型別以明確的 SmartPtr<...> 指定）的情況。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。若無可用的轉換則傳回 nullptr。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於將物件解除封裝為可為 null 的型別。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。若無可用的轉換則傳回空的 nullable。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。無法將非物件型別解除封裝。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

始終傳回 null。

## System::AsCast(const Source\&) function

無法將非物件型別解除封裝。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

始終傳回 null。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於封裝 nullable 物件。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於封裝一般物件。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於封裝一般物件。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於字串解除封裝。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於 nullptr 的轉型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。

## System::AsCast(const Source\&) function

使用 'as' 運算子將來源型別轉換為結果型別。用於陣列之間的轉型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| Source | 來源型別。 |
| Result | 結果型別。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 以進行轉型。 |

### 傳回值

轉型結果。若任何陣列成員皆無可用的轉換則傳回 nullptr。

## 另請參閱

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)