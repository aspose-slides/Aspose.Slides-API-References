---
title: WriteLine()
second_title: Aspose.Slides for C++ API 参考
description: 将当前行终止符输出到由当前对象表示的输出流。
type: docs
weight: 27
url: /zh/system/consoleoutput/writeline/
---
## ConsoleOutput::WriteLine() 方法

将当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine() override
```

## ConsoleOutput::WriteLine(const SharedPtr\<Object\>\&) 方法

将指定对象的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(const SharedPtr<Object> &value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要输出的对象 |

## ConsoleOutput::WriteLine(bool) 方法

将指定 bool 值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(bool value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要输出的对象 |

## ConsoleOutput::WriteLine(char_t) 方法

将指定字符值随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(char_t value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要输出的值 |

## ConsoleOutput::WriteLine(Decimal) 方法

将 [Decimal](../../decimal/) 值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(Decimal value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 要输出的值 |

## ConsoleOutput::WriteLine(double) 方法

将双精度浮点值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(double value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要输出的值 |

## ConsoleOutput::WriteLine(int) 方法

将 32 位整数值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(int value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 要输出的值 |

## ConsoleOutput::WriteLine(int64_t) 方法

将 64 位整数值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(int64_t value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要输出的值 |

## ConsoleOutput::WriteLine(float) 方法

将单精度浮点值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(float value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要输出的值 |

## ConsoleOutput::WriteLine(const String\&) 方法

将指定的字符串对象随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(const String &value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要输出的字符串对象 |

## ConsoleOutput::WriteLine(uint32_t) 方法

将无符号 32 位整数值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(uint32_t value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要输出的值 |

## ConsoleOutput::WriteLine(uint64_t) 方法

将无符号 64 位整数值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(uint64_t value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要输出的值 |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&) 方法

将指定字符数组的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要输出的数组 |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

将指定字符数组的一段值的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 包含要输出值的数组 |
| index | **int32_t** | 要输出元素范围开始的索引 |
| count | **int32_t** | 要输出元素范围的元素数量 |

## ConsoleOutput::WriteLine(const char_t *) 方法

将指定的 C 字符串随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(const char_t *value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要输出的 c 字符串 |

## ConsoleOutput::WriteLine(const TypeInfo\&) 方法

将指定的 [TypeInfo](../../typeinfo/) 对象的字符串表示形式随后加上当前行终止符输出到由当前对象表示的输出流。

```cpp
void System::ConsoleOutput::WriteLine(const TypeInfo &value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要输出的 [TypeInfo](../../typeinfo/) 对象 |

## ConsoleOutput::WriteLine(const char *) 方法




```cpp
void System::ConsoleOutput::WriteLine(const char *)=delete
```

## 另见

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)