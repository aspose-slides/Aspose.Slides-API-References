---
title: operator==()
second_title: Aspose.Slides for C++ API 參考文件
description: 等值比較運算子。
type: docs
weight: 300
url: /zh-hant/system/string/operator_equal_equal/
---
## String::operator==(const String&) const 方法

等值比較運算子。

```cpp
bool System::String::operator==(const String &str) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用於比較目前的字串。 |

### 傳回值

如果兩個字串皆為 null，或皆非 null 且相等，則回傳 true；否則回傳 false。

## String::operator==(std::nullptr_t) const 方法

檢查字串是否為 null。使用與 [IsNull()](../isnull/) 呼叫相同的邏輯。

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### 傳回值

如果字串為 null，則回傳 true；否則回傳 false。

## 參見

* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)