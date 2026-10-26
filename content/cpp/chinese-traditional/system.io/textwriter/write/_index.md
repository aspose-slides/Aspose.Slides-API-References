---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定物件的字串表示寫入串流。
type: docs
weight: 105
url: /zh-hant/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) method

將指定物件的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要寫入的物件 |

## TextWriter::Write(bool) method

將指定布林值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **bool** | 要寫入的值 |

## TextWriter::Write(char_t) method

將指定字符寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要寫入的值 |

## TextWriter::Write(Decimal) method

將指定 [Decimal](../../../system/decimal/) 物件的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 要寫入的物件 |

## TextWriter::Write(double) method

將指定雙精度浮點值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(double value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要寫入的值 |

## TextWriter::Write(int) method

將指定 32 位元整數值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(int value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int | 要寫入的值 |

## TextWriter::Write(int64_t) method

將指定 64 位元整數值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int64_t** | 要寫入的值 |

## TextWriter::Write(float) method

將指定單精度浮點值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(float value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要寫入的值 |

## TextWriter::Write(const String\&) method

將指定字串寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要寫入的字串 |

## TextWriter::Write(uint32_t) method

將指定無號 32 位元整數值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint32_t** | 要寫入的值 |

## TextWriter::Write(uint64_t) method

將指定無號 64 位元整數值的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint64_t** | 要寫入的值 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) method

將指定陣列中的所有字元寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入的字元之陣列 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method

將指定字元陣列中指定的 UTF-16 字元子範圍寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入的字元之陣列 |
| index | **int32_t** | 在 **buffer** 中開始寫入子範圍的 0 基索引 |
| count | **int32_t** | 要寫入的子範圍中的字元數；-1 表示子範圍在 **buffer** 陣列結束處結束 |

## TextWriter::Write(const char_t *) method

將指定的 C 字串寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要寫入的 C 字串 |

## TextWriter::Write(const TypeInfo\&) method

將指定 [TypeInfo](../../../system/typeinfo/) 物件的字串表示寫入串流。

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 要寫入的物件 |

## TextWriter::Write(const String\&, const TArgs\&...) method

將指定的值依照指定的格式化字串寫入串流。

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TArgs | 要寫入之值的型別清單 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 字串格式 |
| args | const TArgs\&... | 要寫入的值 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TextWriter](../)
* 類別 [Decimal](../../../system/decimal/)
* 類別 [String](../../../system/string/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)