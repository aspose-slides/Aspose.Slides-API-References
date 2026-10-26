---
title: Trim()
second_title: Aspose.Slides for C++ API 參考文件
description: 從字串的開頭和結尾移除所有空白字元。
type: docs
weight: 677
url: /zh-hant/system/string/trim/
---
## String::Trim() const 方法

從字串的開頭和結尾移除所有空白字元。

```cpp
String System::String::Trim() const
```

### 返回值

[String](../)，開頭和結尾沒有空白字元。

## String::Trim(char_t) const 方法

從字串的開頭和結尾移除所有傳入的字元。

```cpp
String System::String::Trim(char_t ch) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ch | char_t | 要移除的符號。 |

### 返回值

移除結果。

## String::Trim(const String\&) const 方法

從字串的開頭和結尾移除所有傳入字元。

```cpp
String System::String::Trim(const String &anyOf) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../)要移除的字元。 |

### 返回值

[String](../)，不含已移除的字元。

## String::Trim(const ArrayPtr\<char_t\>\&) const 方法

從字串的開頭和結尾移除所有傳入字元。

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)要移除的字元。 |

### 返回值

[String](../)，不含已移除的字元。

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)