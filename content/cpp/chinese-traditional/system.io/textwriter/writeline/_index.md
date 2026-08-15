---
title: WriteLine()
second_title: Aspose.Slides for C++ API 參考文件
description: 將換行終止字元寫入串流。
type: docs
weight: 118
url: /zh-hant/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() 方法

將換行終止字元寫入串流。

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) 方法

將指定物件的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要寫入的物件 |

## TextWriter::WriteLine(bool) 方法

將指定布林值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **bool** | 要寫入的值 |

## TextWriter::WriteLine(char_t) 方法

將指定字元寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要寫入的值 |

## TextWriter::WriteLine(Decimal) 方法

將指定 [Decimal](../../../system/decimal/) 物件的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 要寫入的物件 |

## TextWriter::WriteLine(double) 方法

將指定雙精度浮點值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要寫入的值 |

## TextWriter::WriteLine(int) 方法

將指定 32 位元整數值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int | 要寫入的值 |

## TextWriter::WriteLine(int64_t) 方法

將指定 64 位元整數值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int64_t** | 要寫入的值 |

## TextWriter::WriteLine(float) 方法

將指定單精度浮點值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要寫入的值 |

## TextWriter::WriteLine(const String\&) 方法

將指定字串寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要寫入的字串 |

## TextWriter::WriteLine(uint32_t) 方法

將指定無號 32 位元整數值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint32_t** | 要寫入的值 |

## TextWriter::WriteLine(uint64_t) 方法

將指定無號 64 位元整數值的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint64_t** | 要寫入的值 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) 方法

將指定陣列中的所有字符寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入字元的陣列 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

將指定字元陣列中 UTF-16 字元的指定子區間寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入字元的陣列 |
| index | **int32_t** | 在 **buffer** 中子區間寫入開始位置的零基索引 |
| count | **int32_t** | 要寫入的子區間字元數；-1 表示子區間在 **buffer** 陣列結束處結束 |

## TextWriter::WriteLine(const char_t *) 方法

將指定的 C 字串寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要寫入的 C 字串 |

## TextWriter::WriteLine(const TypeInfo\&) 方法

將指定 [TypeInfo](../../../system/typeinfo/) 物件的字串表示寫入串流，並在其後加入換行終止字元。

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 要寫入的物件 |

## TextWriter::WriteLine(const String\&, const TArgs\&...) 方法

將指定值依據給定格式進行格式化後寫入串流，並在其後加入換行終止字元。

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
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
* Class [TextWriter](../)
* Class [Object](../../../system/object/)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)