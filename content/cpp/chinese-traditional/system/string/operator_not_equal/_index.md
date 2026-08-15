---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考
description: 不等比較運算子。
type: docs
weight: 313
url: /zh-hant/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const 方法


不等比較運算子。

```cpp
bool System::String::operator!=(const String &str) const
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 以比較目前的字串。 |

### 返回值

如果兩個字串皆為 null 或皆非 null 且相等，則返回 false；否則返回 true。

## String::operator!=(std::nullptr_t) const 方法


檢查字串是否為非 null。套用與 [IsNull()](../isnull/) 呼叫相同的邏輯。

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### 返回值

如果字串為 null，則返回 false；否則返回 true。

## 另請參閱

* 類別 [String](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)