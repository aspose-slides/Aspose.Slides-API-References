---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的字符寫入資料流。
type: docs
weight: 40
url: /zh-hant/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) 方法

將指定的字符寫入資料流。

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | char_t | 要寫入的值 |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

將指定字元陣列中指定的子範圍字符寫入資料流。

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入字符的陣列 |
| index | **int32_t** | 在 **buffer** 中子範圍寫入起始位置的 0 起始索引 |
| count | **int32_t** | 要寫入之子範圍的字符數量 |

## StringWriter::Write(const String\&) 方法

將指定的字串寫入資料流。

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要寫入的字串 |

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [StringWriter](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)