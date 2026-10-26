---
title: TrimStart()
second_title: Aspose.Slides for C++ API 參考
description: 從字串開頭移除所有空白字元。
type: docs
weight: 690
url: /zh-hant/system/string/trimstart/
---
## String::TrimStart() const 方法

從字串開頭移除所有空白字元。

```cpp
String System::String::TrimStart() const
```

### 返回值

[String](../) 開頭沒有空白字元的字串。

## String::TrimStart(char_t) const 方法

從字串開頭移除傳入字元的所有出現。

```cpp
String System::String::TrimStart(char_t ch) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ch | char_t | 要移除的符號。 |

### 返回值

移除結果。

## String::TrimStart(const String\&) const 方法

從字串開頭移除傳入字元的所有出現。

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 要移除的字元。 |

### 返回值

[String](../) 移除字元後的字串。

## String::TrimStart(const ArrayPtr\<char_t\>\&) const 方法

從字串開頭移除傳入字元的所有出現。

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 要移除的字元。 |

### 返回值

[String](../) 移除字元後的字串。

## 另見

* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)