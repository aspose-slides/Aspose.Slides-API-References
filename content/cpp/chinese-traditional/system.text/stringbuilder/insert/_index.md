---
title: Insert()
second_title: Aspose.Slides for C++ API 參考
description: 將字串插入建構器的固定位置。
type: docs
weight: 183
url: /zh-hant/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) 方法

將字串插入建構器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 插入字元的位置。 |
| str | const [String](../../../system/string/)\& | 要插入的 [String](../../../system/string/)。 |

### 傳回值

此指標。

## StringBuilder::Insert(int32_t, const String\&, int32_t) 方法

將重複字串插入建構器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 插入字元的位置。 |
| value | const [String](../../../system/string/)\& | 要插入的 [String](../../../system/string/)。 |
| count | **int32_t** | 要重複 **value** 字串的次數。 |

### 傳回值

此指標。

## StringBuilder::Insert(int, char_t) 方法

將字元插入建構器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 插入字元的位置。 |
| ch | char_t | 要插入的字元。 |

### 傳回值

此指標。

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) 方法

將字元插入建構器的固定位置。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 插入字元的位置。 |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 要從 [Array](../../../system/array/) 插入的切片。 |
| startIndex | int | [Array](../../../system/array/) 切片的起始索引。 |
| charCount | int | [Array](../../../system/array/) 切片長度。 |

### 傳回值

此指標。

## StringBuilder::Insert(int, T) 方法

將值插入建構器的固定位置。

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| 參數 | 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | 插入字元的位置。 |
| value | T | 要格式化並插入的值。 |

### 傳回值

此指標。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [StringBuilder](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)