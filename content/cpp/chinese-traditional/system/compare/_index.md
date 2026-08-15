---
title: Compare()
second_title: Aspose.Slides for C++ API 參考
description: 比較兩個值。
type: docs
weight: 2731
url: /zh-hant/system/compare/
---
## System::Compare(const TA\&, const TB\&) 函式

比較兩個值。

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TA | 第一個比較項的類型 |
| TB | 第二個比較項的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const TA\& | 第一個比較項 |
| b | const TB\& | 第二個比較項 |

### 返回值

- 1 如果 **a** 小於 **b**； 0 如果兩個值相等； 1 如果 **a** 大於 **b**

## System::Compare(const TA\&, const TB\&) 函式

比較兩個浮點值。

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TA | 第一個比較項的類型 |
| TB | 第二個比較項的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const TA\& | 第一個比較項 |
| b | const TB\& | 第二個比較項 |

### 返回值

- 1 如果 **a** 小於 **b**； 0 如果兩個值相等； 1 如果 **a** 大於 **b**

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)