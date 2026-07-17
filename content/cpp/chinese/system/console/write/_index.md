---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定对象的字符串表示输出到标准输出流。
type: docs
weight: 1
url: /zh/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) 方法

将指定对象的字符串表示输出到标准输出流。

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要输出的对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) 要输出 |

## Console::Write(bool) 方法

将 bool 值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(bool value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要输出的值 |

## Console::Write(char_t) 方法

将指定的字符值输出到标准输出流。

```cpp
static void System::Console::Write(char_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要输出的值 |

## Console::Write(const ArrayPtr\<char_t\>\&) 方法

将指定字符数组的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要输出的数组 |

## Console::Write(const Decimal\&) 方法

将 [Decimal](../../decimal/) 值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(const Decimal &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要输出的值 |

## Console::Write(double) 方法

将双精度浮点值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(double value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要输出的值 |

## Console::Write(float) 方法

将单精度浮点值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(float value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要输出的值 |

## Console::Write(int32_t) 方法

将 32 位整数值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(int32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int32_t** | 要输出的值 |

## Console::Write(int64_t) 方法

将 64 位整数值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要输出的值 |

## Console::Write(const String\&) 方法

将指定的字符串对象输出到标准输出流。

```cpp
static void System::Console::Write(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要输出的字符串对象 |

## Console::Write(const char_t *) 方法

将指定的 c 字符串输出到标准输出流。

```cpp
static void System::Console::Write(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要输出的 c 字符串 |

## Console::Write(const TypeInfo\&) 方法

将 [TypeInfo](../../typeinfo/) 值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要输出的值 |

## Console::Write(uint32_t) 方法

将无符号 32 位整数值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(uint32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要输出的值 |

## Console::Write(uint64_t) 方法

将无符号 64 位整数值的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(uint64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要输出的值 |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

将指定字符数组的指定范围的字符串表示输出到标准输出流。

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 字符数组 |
| index | **int32_t** | 输出范围在数组中的起始索引 |
| count | **int32_t** | 要输出的范围内的元素数量 |

## Console::Write(const String\&, Args\&&...) 方法

将根据指定格式格式化的指定参数的字符串表示输出到标准输出流。

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| 类型 | 要输出的值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 字符串格式 |
| args | Args\&&... | 要输出的值 |

## Console::Write(const char *) 方法




```cpp
static void System::Console::Write(const char *)=delete
```

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [Console](../)
* 类 [Decimal](../../decimal/)
* 类 [String](../../string/)
* 类 [TypeInfo](../../typeinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)