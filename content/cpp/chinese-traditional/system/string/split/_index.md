---
title: Split()
second_title: Aspose.Slides for C++ API 參考文件
description: 依字元切割字串。
type: docs
weight: 768
url: /zh-hant/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const 方法

依字元切割字串。

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | char_t | 要用來切割字串的字元。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(char_t, int32_t, StringSplitOptions) const 方法

依字元切割字串。

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | char_t | 要用來切割字串的字元。 |
| count | **int32_t** | 要返回的子字串的最大數量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(char_t, char_t, StringSplitOptions) const 方法

依兩個字元中的任一個切割字串。

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separatorA | char_t | 用於切割字串的第一個字元。 |
| separatorB | char_t | 用於切割字串的第二個字元。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const 方法

依所指定的字元之一切割字串。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 的分隔字元。若為空，任何空白字元皆視為分隔字元。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const 方法

依所指定的字元之一切割字串。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 的分隔字元。若為空，任何空白字元皆視為分隔字元。 |
| count | **int32_t** | 要返回的子字串的最大數量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(const String\&, StringSplitOptions) const 方法

以子字串作為分隔符切割字串。

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | const [String](../)\& | 作為分隔字串的子字串。若為空，空白字元作為分隔字元。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(const String\&, int, StringSplitOptions) const 方法

以子字串作為分隔符切割字串。

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separator | const [String](../)\& | 作為分隔字串的子字串。若為空，空白字元作為分隔字元。 |
| count | int | 分割陣列中元素的最大數量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const 方法

以子字串作為分隔符切割字串。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) 的分隔字串。若為空，則不執行切割。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const 方法

以子字串作為分隔符切割字串。目前僅支援零或一個元素的分隔字串陣列。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) 的分隔字串。若為空，則不執行切割。 |
| count | int | 分割陣列中元素的最大數量。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 切割選項。 |

### 返回值

[Array](../../array/) 的子字串。

## 另請參閱

* 列舉 [StringSplitOptions](../../stringsplitoptions/)
* 型別別名 [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)