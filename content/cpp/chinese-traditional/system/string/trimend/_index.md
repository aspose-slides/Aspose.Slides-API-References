---
title: TrimEnd()
second_title: Aspose.Slides C++ API 參考
description: 從字串尾端移除所有空白字元。
type: docs
weight: 703
url: /zh-hant/system/string/trimend/
---
## String::TrimEnd() const 方法

從字串尾端移除所有空白字元。

```cpp
String System::String::TrimEnd() const
```

### 返回值

[String](../) 開頭沒有空白字元。

## String::TrimEnd(char_t) const 方法

從字串尾端移除所有傳入字元的出現次數。

```cpp
String System::String::TrimEnd(char_t ch) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| ch | char_t | 要移除的符號。 |

### 返回值

移除結果。

## String::TrimEnd(const String\&) const 方法

從字串尾端移除所有傳入的字元。

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 要移除的字元。 |

### 返回值

[String](../) 不含已移除的字元。

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const 方法

從字串尾端移除所有傳入的字元。

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要移除的字元。 |

### 返回值

[String](../) 不含已移除的字元。

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)