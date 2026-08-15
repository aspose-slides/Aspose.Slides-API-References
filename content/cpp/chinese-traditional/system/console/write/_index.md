---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 將指定物件的字串表示輸出至標準輸出串流。
type: docs
weight: 1
url: /zh-hant/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) 方法

將指定物件的字串表示輸出至標準輸出串流。

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 要輸出的物件類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) 要輸出的 |

## Console::Write(bool) 方法

將 bool 值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(bool value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要輸出的值 |

## Console::Write(char_t) 方法

將指定的字元值輸出至標準輸出串流。

```cpp
static void System::Console::Write(char_t value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | char_t | 要輸出的值 |

## Console::Write(const ArrayPtr\<char_t\>\&) 方法

將指定字元陣列的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要輸出的陣列 |

## Console::Write(const Decimal\&) 方法

將 [Decimal](../../decimal/) 值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(const Decimal &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要輸出的值 |

## Console::Write(double) 方法

將 double 精度浮點值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(double value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **double** | 要輸出的值 |

## Console::Write(float) 方法

將 float 精度浮點值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(float value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **float** | 要輸出的值 |

## Console::Write(int32_t) 方法

將 32 位元整數值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(int32_t value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **int32_t** | 要輸出的值 |

## Console::Write(int64_t) 方法

將 64 位元整數值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(int64_t value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要輸出的值 |

## Console::Write(const String\&) 方法

將指定的字串物件輸出至標準輸出串流。

```cpp
static void System::Console::Write(const String &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要輸出的字串物件 |

## Console::Write(const char_t *) 方法

將指定的 c-string 輸出至標準輸出串流。

```cpp
static void System::Console::Write(const char_t *value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要輸出的 c-string |

## Console::Write(const TypeInfo\&) 方法

將 [TypeInfo](../../typeinfo/) 值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要輸出的值 |

## Console::Write(uint32_t) 方法

將 unsigned 32 位元整數值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(uint32_t value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要輸出的值 |

## Console::Write(uint64_t) 方法

將 unsigned 64 位元整數值的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(uint64_t value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要輸出的值 |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

將指定字元陣列中指定範圍的字串表示輸出至標準輸出串流。

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 字元陣列 |
| index | **int32_t** | 陣列中開始輸出範圍的索引 |
| count | **int32_t** | 要輸出的範圍內元素的數量 |

## Console::Write(const String\&, Args\&&...) 方法

將指定引數依照指定格式化後的字串表示輸出至標準輸出串流。

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| The | 要輸出的值類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 字串格式 |
| args | Args\&&... | 要輸出的值 |

## Console::Write(const char *) 方法




```cpp
static void System::Console::Write(const char *)=delete
```

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [Console](../)
* 類別 [Decimal](../../decimal/)
* 類別 [String](../../string/)
* 類別 [TypeInfo](../../typeinfo/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)