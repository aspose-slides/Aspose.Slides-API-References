---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考
description: 判斷委託集合是否非空。
type: docs
weight: 131
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_not_equal/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator!=(const std::nullptr_t\&) const 方法

判斷委託集合是否非空。

```cpp
bool System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator!=(const std::nullptr_t &) const
```


### 返回值

True if the delegate collection is not empty, otherwise - false

## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator!=(const MulticastDelegate\&) const 方法


判斷兩個 MulticastDelegate 實例——當前物件和指定物件——是否不相等。

```cpp
bool System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator!=(const MulticastDelegate &other) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const [MulticastDelegate](../multicastdelegate/)\& | 用於比較的 MulticastDelegate 物件 |

### 返回值

如果兩個物件表示相同的委託集合則返回 true，否則返回 false

## 另請參閱

* 方法 [MulticastDelegate](../multicastdelegate/)
* 類別 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)