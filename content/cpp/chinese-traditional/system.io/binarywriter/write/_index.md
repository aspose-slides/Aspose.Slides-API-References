---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的無號 8 位元整數值寫入輸出串流。
type: docs
weight: 92
url: /zh-hant/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) 方法

將指定的無號 8 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint8_t** | 要寫入的值 |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) 方法

將指定的位元組子範圍從指定的位元組陣列寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列 |
| index | int | **buffer** 中子範圍寫入開始位置的零基索引 |
| count | int | 要寫入之子範圍的元素數量；-1 表示子範圍在 **buffer** 陣列結束處結束 |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) 方法

將指定的 UTF-16 字元子範圍從指定的字元陣列寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要寫入之字元的陣列 |
| index | int | **buffer** 中子範圍寫入開始位置的零基索引 |
| count | int | 要寫入之子範圍的字元數量；-1 表示子範圍在 **buffer** 陣列結束處結束 |

## BinaryWriter::Write(bool) 方法

將單一位元組寫入輸出串流：若 **value** 為 `true` 則寫入 0，若 **value** 為 `false` 則寫入 1。

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **bool** | 指定寫入輸出串流之位元組值的布林值 |

## BinaryWriter::Write(char16_t) 方法

將指定的 16 位元寬字元值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char16_t | 要寫入的值 |

## BinaryWriter::Write(int16_t) 方法

將指定的 16 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int16_t** | 要寫入的值 |

## BinaryWriter::Write(int) 方法

將指定的 32 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int | 要寫入的值 |

## BinaryWriter::Write(int64_t) 方法

將指定的 64 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int64_t** | 要寫入的值 |

## BinaryWriter::Write(uint16_t) 方法

將指定的無號 16 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint16_t** | 要寫入的值 |

## BinaryWriter::Write(uint32_t) 方法

將指定的無號 32 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint32_t** | 要寫入的值 |

## BinaryWriter::Write(uint64_t) 方法

將指定的無號 64 位元整數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint64_t** | 要寫入的值 |

## BinaryWriter::Write(float) 方法

將指定的單精度浮點數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要寫入的值 |

## BinaryWriter::Write(double) 方法

將指定的雙精度浮點數值寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要寫入的值 |

## BinaryWriter::Write(const Decimal\&) 方法

將指定的 [Decimal](../../../system/decimal/) 值的位元組表示寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | 要寫入的值 |

## BinaryWriter::Write(const String\&) 方法

將當前編碼下的長度前置字串寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要寫入的字串 |

## BinaryWriter::Write(const char_t *) 方法

將當前編碼下的長度前置字串寫入輸出串流。

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要寫入的 C 字串 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)