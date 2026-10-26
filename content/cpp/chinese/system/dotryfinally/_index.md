---
title: DoTryFinally()
second_title: Aspose.Slides C++ API 参考
description: 模拟 C# 的 try[-catch]-finally 语句行为的单一函数。在将 C# 的 try[-catch]-finally 语句翻译为代码时，如果翻译器选项 finally_statement_as_lambda 设置为 true，则该语句会被翻译为对本方法的调用。
type: docs
weight: 2406
url: /zh/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) 函数

模拟 C# 的 try[-catch]-finally 语句行为的单一函数。在将 C# 的 try[-catch]-finally 语句翻译为代码时，如果翻译器选项 finally_statement_as_lambda 设置为 true，则该语句会被翻译为对本方法的调用。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 实现被模拟的 try[-catch]-finally 语句中 try[-catch] 部分的函数对象的类型 |
| F | 实现被模拟的 try[-catch]-finally 语句中 finally 部分的函数对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryBlock | T\&& | 其函数体包含被模拟的 try[-catch]-finally 语句中 try[-catch] 部分实现的函数对象 |
| finallyBlock | F\&& | 其函数体包含被模拟的 try[-catch]-finally 语句中 finally 部分实现的函数对象 |

## System::DoTryFinally(T\&&, F\&&) 函数

模拟 C# 的 try[-catch]-finally 语句行为的单一函数。在将 C# 的 try[-catch]-finally 语句翻译为代码时，如果翻译器选项 finally_statement_as_lambda 设置为 true，则该语句会被翻译为对本方法的调用。此重载处理实现 try[-catch]-finally 语句中 try[-catch] 部分的函数对象返回值为 bool 的情况。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 实现被模拟的 try[-catch]-finally 语句中 try[-catch] 部分的函数对象的类型 |
| F | 实现被模拟的 try[-catch]-finally 语句中 finally 部分的函数对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryBlock | T\&& | 其函数体包含被模拟的 try[-catch]-finally 语句中 try[-catch] 部分实现的函数对象 |
| finallyBlock | F\&& | 其函数体包含被模拟的 try[-catch]-finally 语句中 finally 部分实现的函数对象 |

## System::DoTryFinally(T\&&, F\&&) 函数

模拟 C# 的 try[-catch]-finally 语句行为的单一函数。在将 C# 的 try[-catch]-finally 语句翻译为代码时，如果翻译器选项 finally_statement_as_lambda 设置为 true，则该语句会被翻译为对本方法的调用。此重载处理实现 try[-catch]-finally 语句中 try[-catch] 部分的函数对象返回值为 bool& 的情况。

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 实现被模拟的 try[-catch]-finally 语句中 try[-catch] 部分的函数对象的类型 |
| F | 实现被模拟的 try[-catch]-finally 语句中 finally 部分的函数对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryBlock | T\&& | 其函数体包含被模拟的 try[-catch]-finally 语句中 try[-catch] 部分实现的函数对象 |
| finallyBlock | F\&& | 其函数体包含被模拟的 try[-catch]-finally 语句中 finally 部分实现的函数对象 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)