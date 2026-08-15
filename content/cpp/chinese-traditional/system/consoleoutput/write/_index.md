---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定 bool 值的字串表示輸出至由目前物件所代表的輸出串流。
type: docs
weight: 14
url: /zh-hant/system/consoleoutput/write/
---
## ConsoleOutput::Write(bool) 方法

將指定 bool 值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(bool value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **bool** | 要輸出的值 |

## ConsoleOutput::Write(const SharedPtr\<Object\>\&) 方法

將指定物件的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(const SharedPtr<Object> &value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要輸出的物件 |

## ConsoleOutput::Write(char_t) 方法

將指定的字元值輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(char_t value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char_t | 要輸出的值 |

## ConsoleOutput::Write(Decimal) 方法

將 [Decimal](../../decimal/) 值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(Decimal value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 要輸出的值 |

## ConsoleOutput::Write(double) 方法

將雙精度浮點數值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(double value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **double** | 要輸出的值 |

## ConsoleOutput::Write(int32_t) 方法

將 32 位元整數值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(int32_t value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int32_t** | 要輸出的值 |

## ConsoleOutput::Write(int64_t) 方法

將 64 位元整數值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(int64_t value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int64_t** | 要輸出的值 |

## ConsoleOutput::Write(float) 方法

將單精度浮點數值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(float value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要輸出的值 |

## ConsoleOutput::Write(const String\&) 方法

將指定的字串物件輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(const String &value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要輸出的字串物件 |

## ConsoleOutput::Write(uint32_t) 方法

將無號 32 位元整數值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(uint32_t value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint32_t** | 要輸出的值 |

## ConsoleOutput::Write(uint64_t) 方法

將無號 64 位元整數值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(uint64_t value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **uint64_t** | 要輸出的值 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&) 方法

將指定字元陣列的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要輸出的陣列 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

將指定字元陣列中一段範圍的值的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 包含要輸出的值的陣列 |
| index | **int32_t** | 要輸出的元素範圍開始的索引 |
| count | **int32_t** | 要輸出的元素範圍內的元素數量 |

## ConsoleOutput::Write(const char_t *) 方法

將指定的 C 字串輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(const char_t *value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const char_t * | 要輸出的 C 字串 |

## ConsoleOutput::Write(const TypeInfo\&) 方法

將指定 [TypeInfo](../../typeinfo/) 物件的字串表示輸出至由目前物件所代表的輸出串流。

```cpp
void System::ConsoleOutput::Write(const TypeInfo &value) override
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要輸出的 [TypeInfo](../../typeinfo/) 物件 |

## ConsoleOutput::Write(const char *) 方法

```cpp
void System::ConsoleOutput::Write(const char *)=delete
```

## 相關參考

* 型別定義 [SharedPtr](../../sharedptr/)
* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [ConsoleOutput](../)
* 類別 [Object](../../object/)
* 類別 [Decimal](../../decimal/)
* 類別 [String](../../string/)
* 類別 [TypeInfo](../../typeinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)