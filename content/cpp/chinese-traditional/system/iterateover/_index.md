---
title: IterateOver()
second_title: Aspose.Slides for C++ API 參考
description: "此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對沒有 begin()、end() 方法的 Enumerable，使用目標類型參數，語法為 (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /zh-hant/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對沒有 `begin()`、`end()` 方法的 Enumerable，使用目標類型參數，語法為 (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標類型，必須由迭代器返回 |
| Enumerable | 被封裝物件的型別 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對沒有 `begin()`、`end()` 方法的 Enumerable，使用預設目標類型參數，語法為 (auto& value : IterateOver(enumerable))，相當於以下 C# 程式碼 `foreach (var value in enumerable)`

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Enumerable | 被封裝物件的型別 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對具有 `begin()`、`end()` 方法的 Enumerable，使用預設目標類型參數，語法為 (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Enumerable | 被封裝物件的型別 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對具有 `begin()`、`end()` 方法的 Enumerable，目標類型與迭代器的原始 `value_type` 相同。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Enumerable | 被封裝物件的型別 |
| T | 必須由迭代器返回的目標類型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對具有 `begin()`、`end()` 方法的 Enumerable，目標類型與迭代器的原始 `value_type` 不同。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Enumerable | 被封裝物件的型別 |
| T | 必須由迭代器返回的目標類型 |

## System::IterateOver(const Enumerable *) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對 Enumerable，使用預設目標類型。

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Enumerable | 被封裝物件的型別 |

## System::IterateOver(const Enumerable *) 函數

此函式屬性封裝可列舉（或可迭代）物件，使其能在基於範圍的 for 迴圈中使用。此重載針對沒有 `begin()`、`end()` 方法的 Enumerable，使用目標類型參數，語法為 (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標類型，必須由迭代器返回 |
| Enumerable | 被封裝物件的型別 |

## 參見

* 類別 [SmartPtr](../smartptr/)
* 結構 [IsSmartPtr](../issmartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)