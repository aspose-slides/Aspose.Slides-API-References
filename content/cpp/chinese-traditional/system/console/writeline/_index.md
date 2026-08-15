---
title: WriteLine()
second_title: Aspose.Slides for C++ API 參考
description: 將目前的換行字元輸出至標準輸出串流。
type: docs
weight: 14
url: /zh-hant/system/console/writeline/
---
## Console::WriteLine() 方法

將目前的換行字元輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine()
```

## Console::WriteLine(const SharedPtr\<T\>\&) 方法

將指定物件的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
template<class T> static void System::Console::WriteLine(const SharedPtr<T> &object)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| T | 要輸出的物件型別 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | 要輸出的 [Object](../../object/) |

## Console::WriteLine(bool) 方法

將 bool 值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(bool value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **bool** | 要輸出的值 |

## Console::WriteLine(char_t) 方法

將指定的字元值，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(char_t value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | 要輸出的值 |

## Console::WriteLine(const ArrayPtr\<char_t\>\&) 方法

將指定字元陣列的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要輸出的陣列 |

## Console::WriteLine(const Decimal\&) 方法

將 [Decimal](../../decimal/) 值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const Decimal &value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要輸出的值 |

## Console::WriteLine(double) 方法

將 double 精度浮點值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(double value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 要輸出的值 |

## Console::WriteLine(float) 方法

將單精度浮點值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(float value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | 要輸出的值 |

## Console::WriteLine(int32_t) 方法

將 32 位元整數值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(int32_t value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int32_t** | 要輸出的值 |

## Console::WriteLine(int64_t) 方法

將 64 位元整數值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(int64_t value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int64_t** | 要輸出的值 |

## Console::WriteLine(const String\&) 方法

將指定的字串物件，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const String &value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要輸出的字串物件 |

## Console::WriteLine(const char_t *) 方法

將指定的 C 字串，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const char_t *value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | 要輸出的 C 字串 |

## Console::WriteLine(const TypeInfo\&) 方法

將 [TypeInfo](../../typeinfo/) 值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const TypeInfo &value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要輸出的值 |

## Console::WriteLine(uint32_t) 方法

將無號 32 位元整數值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(uint32_t value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | 要輸出的值 |

## Console::WriteLine(uint64_t) 方法

將無號 64 位元整數值的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(uint64_t value)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | 要輸出的值 |

## Console::WriteLine(const ArrayPtr\<char_t\>\&, int, int) 方法

將指定字元陣列的指定範圍之字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer, int index, int count)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 字元陣列 |
| index | int | 範圍開始的陣列索引 |
| count | int | 範圍內的元素個數 |

## Console::WriteLine(const Exception\&) 方法

將指定的 Exception 物件的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
static void System::Console::WriteLine(const Exception &e)
```

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| e | const [Exception](../../exception/)\& | 要輸出的值 |

## Console::WriteLine(const String\&, Args\&&...) 方法

將指定參數依照提供的格式化字串進行格式化後的字串表示形式，接著目前的換行字元，輸出至標準輸出串流。

```cpp
template<class...> static void System::Console::WriteLine(const String &format, Args &&... args)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| The | 要輸出的值的型別 |

### 引數

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | 字串格式 |
| args | Args\&&... | 要輸出的值 |

## Console::WriteLine(const char *) 方法




```cpp
static void System::Console::WriteLine(const char *)=delete
```

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Exception](../../exception/)
* 類別 [Console](../)
* 類別 [Decimal](../../decimal/)
* 類別 [String](../../string/)
* 類別 [TypeInfo](../../typeinfo/)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)