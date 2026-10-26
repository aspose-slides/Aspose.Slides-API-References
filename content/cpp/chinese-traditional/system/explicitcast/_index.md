---
title: ExplicitCast()
second_title: Aspose.Slides for C++ API 參考
description: 使用顯式轉型將來源類型轉換為結果類型。當來源類型與結果類型相同時使用。
type: docs
weight: 2627
url: /zh-hant/system/explicitcast/
---
## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。當來源類型與結果類型相同時使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。需要簡單的類似建構子轉型時使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於例外包裝器。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於將物件轉型為例外。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。當來源與結果皆為智慧指標（結果類型中未使用顯式 SmartPtr<...>）時使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(Source) function

使用顯式轉型將來源類型轉換為結果類型。在將原始指標轉換為智慧指標時使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | Source | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。當來源與結果皆為智慧指標（結果類型中使用顯式 SmartPtr<...>）時使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於將物件拆箱為可為空類型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於將可為空類型裝箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於將可為空物件拆箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於列舉裝箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。當值類型應以智慧指標方式參照，且需要將值類型複製到堆上時使用（於以介面類型為約束的泛型，但以實作此介面的結構為特殊化時）。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於從值類型取得介面。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於一般裝箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於 [System::String](../string/) 裝箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於拆箱介面。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於一般拆箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於 nullptr 轉型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## System::ExplicitCast(const Source\&) function

使用顯式轉型將來源類型轉換為結果類型。用於陣列之間的轉型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| Source | 來源類型。 |
| Result | 結果類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 需要轉型。 |

### 返回值

轉型結果。

## 參見

* 類型別名 [Exception](../exception/)
* 類別 [SmartPtr](../smartptr/)
* 類別 [BoxedValueBase](../boxedvaluebase/)
* 結構 [CastResult](../castresult/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)