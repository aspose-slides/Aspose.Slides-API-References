---
title: Is()
second_title: Aspose.Slides for C++ API 參考
description: 實作「is」宣告模式轉譯。
type: docs
weight: 2302
url: /zh-hant/system/is/
---
## System::Is(const ExpressionT&, ResultT&) 函式


實作 'is' 宣告模式轉譯。

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| PatternT | 要檢查的型別。 |
| ExpressionT | 左側表達式型別。 |
| ResultT | 結果表達式的型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | const ExpressionT& | 將被檢查的表達式。 |
| result | ResultT& | 會被指派為檢查後型別的變數。 |

### 傳回值

若型別檢查成功則傳回 true，否則傳回 false。

## System::Is(const ExpressionT&, const ConstantT&) 函式


實作 'is' 常數模式轉譯。

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| ExpressionT | 左側表達式型別。 |
| ConstantT | 常數表達式的型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | const ExpressionT& | 將被檢查的表達式。 |
| constant | const ConstantT& | 將與左側表達式比較的常數。 |

### 傳回值

若型別檢查成功則傳回 true，否則傳回 false。

## System::Is(const E&, const A&) 函式


頂層匹配函式。將模式套用到值上。

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| A | 模式型別（必須繼承自 Details::Pattern）。 |
| E | 要匹配的值的型別。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| e | const E& | 要匹配的值。 |
| a | const A& | 要套用的模式。 |

### 傳回值

若模式與值匹配則傳回 true。

## 相關參考

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)