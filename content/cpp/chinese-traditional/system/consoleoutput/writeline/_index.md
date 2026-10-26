---
title: WriteLine()
second_title: Aspose.Slides for C++ API 參考
description: 將目前的行終止符輸出到由目前物件表示的輸出串流。
type: docs
weight: 27
url: /zh-hant/system/consoleoutput/writeline/
---
## ConsoleOutput::WriteLine() 方法

將目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine() override
```

## ConsoleOutput::WriteLine(const SharedPtr\<Object\>\&) 方法

將指定物件的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(const SharedPtr<Object> &value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要輸出的物件 |

## ConsoleOutput::WriteLine(bool) 方法

將指定 bool 值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(bool value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要輸出的物件 |

## ConsoleOutput::WriteLine(char_t) 方法

將指定字元值以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(char_t value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | char_t | 要輸出的值 |

## ConsoleOutput::WriteLine(Decimal) 方法

將 [Decimal](../../decimal/) 值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(Decimal value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 要輸出的值 |

## ConsoleOutput::WriteLine(double) 方法

將雙精度浮點數值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(double value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **double** | 要輸出的值 |

## ConsoleOutput::WriteLine(int) 方法

將 32 位元整數值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(int value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int | 要輸出的值 |

## ConsoleOutput::WriteLine(int64_t) 方法

將 64 位元整數值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(int64_t value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要輸出的值 |

## ConsoleOutput::WriteLine(float) 方法

將單精度浮點數值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(float value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **float** | 要輸出的值 |

## ConsoleOutput::WriteLine(const String\&) 方法

將指定的字串物件以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(const String &value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要輸出的字串物件 |

## ConsoleOutput::WriteLine(uint32_t) 方法

將無號 32 位元整數值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(uint32_t value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要輸出的值 |

## ConsoleOutput::WriteLine(uint64_t) 方法

將無號 64 位元整數值的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(uint64_t value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要輸出的值 |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&) 方法

將指定字元陣列的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要輸出的陣列 |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

將指定字元陣列中一段範圍的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 含有要輸出值的陣列 |
| index | **int32_t** | 要輸出的元素範圍起始索引 |
| count | **int32_t** | 要輸出的元素範圍內的元素數量 |

## ConsoleOutput::WriteLine(const char_t *) 方法

將指定的 C 字串以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(const char_t *value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要輸出的 C 字串 |

## ConsoleOutput::WriteLine(const TypeInfo\&) 方法

將指定 [TypeInfo](../../typeinfo/) 物件的字串表示以及目前的行終止符輸出到由目前物件表示的輸出串流。

```cpp
void System::ConsoleOutput::WriteLine(const TypeInfo &value) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要輸出的 [TypeInfo](../../typeinfo/) 物件 |

## ConsoleOutput::WriteLine(const char *) 方法




```cpp
void System::ConsoleOutput::WriteLine(const char *)=delete
```

## 相關參考

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)