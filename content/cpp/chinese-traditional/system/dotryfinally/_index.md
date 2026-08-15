---
title: DoTryFinally()
second_title: Aspose.Slides C++ API 參考
description: 此單一函式模擬 C# 的 try[-catch]-finally 陳述式的行為。當使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被翻譯為呼叫此方法。
type: docs
weight: 2445
url: /zh-hant/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) 函式

此單一函式模擬 C# 的 try[-catch]-finally 陳述式的行為。當使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被翻譯為呼叫此方法。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 實作被模擬之 try[-catch]-finally 陳述式中 try[-catch] 部分之函式物件的型別 |
| F | 實作被模擬之 try[-catch]-finally 陳述式中 finally 部分之函式物件的型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tryBlock | T\&& | 其主體包含實作被模擬之 try[-catch]-finally 陳述式中 try[-catch] 部分之函式物件 |
| finallyBlock | F\&& | 其主體包含實作被模擬之 try[-catch]-finally 陳述式中 finally 部分之函式物件 |

## System::DoTryFinally(T\&&, F\&&) 函式

此單一函式模擬 C# 的 try[-catch]-finally 陳述式的行為。當使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被翻譯為呼叫此方法。此載入處理返回值為 bool 的情況。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 實作被模擬之 try[-catch]-finally 陳述式中 try[-catch] 部分之函式物件的型別 |
| F | 實作被模擬之 try[-catch]-finally 陳述式中 finally 部分之函式物件的型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tryBlock | T\&& | 其主體包含實作被模擬之 try[-catch]-finally 陳述式中 try[-catch] 部分之函式物件 |
| finallyBlock | F\&& | 其主體包含實作被模擬之 try[-catch]-finally 陳述式中 finally 部分之函式物件 |

## System::DoTryFinally(T\&&, F\&&) 函式

此單一函式模擬 C# 的 try[-catch]-finally 陳述式的行為。當使用翻譯器選項 finally_statement_as_lambda 設為 true 時，C# 的 try[-catch]-finally 陳述式會被翻譯為呼叫此方法。此載入處理返回值為 bool& 的情況。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 實作被模擬之 try[-catch]-finally 陳述式中 try[-catch] 部分之函式物件的型別 |
| F | 實作被模擬之 try[-catch]-finally 陳述式中 finally 部分之函式物件的型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tryBlock | T\&& | 其主體包含實作被模擬之 try[-catch]-finally 陳述式中 try[-catch] 部分之函式物件 |
| finallyBlock | F\&& | 其主體包含實作被模擬之 try[-catch]-finally 陳述式中 finally 部分之函式物件 |

## 另請參閱

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)