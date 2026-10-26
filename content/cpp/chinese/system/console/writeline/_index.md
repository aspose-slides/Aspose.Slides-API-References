---
title: WriteLine()
second_title: Aspose.Slides for C++ API 参考
description: 将当前行终止符输出到标准输出流。
type: docs
weight: 14
url: /zh/system/console/writeline/
---
## Console::WriteLine() 方法

将当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine()
```

## Console::WriteLine(const SharedPtr\<T\>\&) 方法

将指定对象的字符串表示以及当前行终止符输出到标准输出流。

```cpp
template<class T> static void System::Console::WriteLine(const SharedPtr<T> &object)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要输出的对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) 用于输出 |

## Console::WriteLine(bool) 方法

将 bool 值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(bool value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要输出的值 |

## Console::WriteLine(char_t) 方法

将指定的字符值以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(char_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要输出的值 |

## Console::WriteLine(const ArrayPtr\<char_t\>\&) 方法

将指定字符数组的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要输出的数组 |

## Console::WriteLine(const Decimal\&) 方法

将 [Decimal](../../decimal/) 值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const Decimal &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要输出的值 |

## Console::WriteLine(double) 方法

将双精度浮点值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(double value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要输出的值 |

## Console::WriteLine(float) 方法

将单精度浮点值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(float value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要输出的值 |

## Console::WriteLine(int32_t) 方法

将 32 位整数值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(int32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int32_t** | 要输出的值 |

## Console::WriteLine(int64_t) 方法

将 64 位整数值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要输出的值 |

## Console::WriteLine(const String\&) 方法

将指定的字符串对象以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要输出的字符串对象 |

## Console::WriteLine(const char_t *) 方法

将指定的 C 风格字符串以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要输出的 C 风格字符串 |

## Console::WriteLine(const TypeInfo\&) 方法

将 [TypeInfo](../../typeinfo/) 值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const TypeInfo &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要输出的值 |

## Console::WriteLine(uint32_t) 方法

将无符号 32 位整数值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(uint32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要输出的值 |

## Console::WriteLine(uint64_t) 方法

将无符号 64 位整数值的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(uint64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要输出的值 |

## Console::WriteLine(const ArrayPtr\<char_t\>\&, int, int) 方法

将指定字符数组的指定范围的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer, int index, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 字符数组 |
| index | int | 要输出的范围在数组中的起始索引 |
| count | int | 要输出的范围的元素数量 |

## Console::WriteLine(const Exception\&) 方法

将指定 Exception 对象的字符串表示以及当前行终止符输出到标准输出流。

```cpp
static void System::Console::WriteLine(const Exception &e)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| e | const [Exception](../../exception/)\& | 要输出的值 |

## Console::WriteLine(const String\&, Args\&&...) 方法

将按照指定格式格式化的指定参数的字符串表示以及当前行终止符输出到标准输出流。

```cpp
template<class...> static void System::Console::WriteLine(const String &format, Args &&... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| The | 要输出的值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 字符串格式 |
| args | Args\&&... | 要输出的值 |

## Console::WriteLine(const char *) 方法



```cpp
static void System::Console::WriteLine(const char *)=delete
```

## See Also

* 类型定义 [SharedPtr](../../sharedptr/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [Exception](../../exception/)
* 类 [Console](../)
* 类 [Decimal](../../decimal/)
* 类 [String](../../string/)
* 类 [TypeInfo](../../typeinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)