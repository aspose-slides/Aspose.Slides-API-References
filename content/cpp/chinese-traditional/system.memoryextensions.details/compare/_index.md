---
title: Compare()
second_title: Aspose.Slides C++ API 參考
description: 比較兩個智慧指標。
type: docs
weight: 1
url: /zh-hant/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) 函式


比較兩個智慧指標。

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 第一個智慧指標的類型 |
| U | 第二個智慧指標的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 第一個智慧指標 |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | 第二個智慧指標 |

### 返回值

[Comparison](../../system/comparison/) 結果 (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) 函式


比較兩個算術值。

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 算術類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const T\& | 第一個值 |
| b | const T\& | 第二個值 |

### 返回值

[Comparison](../../system/comparison/) 結果 (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) 函式


比較智慧指標與值。

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 智慧指標所指向的類型 |
| U | 值的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 智慧指標 |
| b | const U\& | 值 |

### 返回值

[Comparison](../../system/comparison/) 結果 (0 if equal, -1 if a < b, 1 if a > b)

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)