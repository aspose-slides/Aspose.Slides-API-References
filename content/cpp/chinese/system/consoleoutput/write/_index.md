---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定 bool 值的字符串表示输出到当前对象表示的输出流。
type: docs
weight: 14
url: /zh/system/consoleoutput/write/
---
## ConsoleOutput::Write(bool) 方法


将指定 bool 值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(bool value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **bool** | 要输出的值 |

## ConsoleOutput::Write(const SharedPtr\<Object\>\&) 方法


将指定对象的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(const SharedPtr<Object> &value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要输出的对象 |

## ConsoleOutput::Write(char_t) 方法


将指定字符值输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(char_t value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要输出的值 |

## ConsoleOutput::Write(Decimal) 方法


将 [Decimal](../../decimal/) 值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(Decimal value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 要输出的值 |

## ConsoleOutput::Write(double) 方法


将双精度浮点值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(double value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要输出的值 |

## ConsoleOutput::Write(int32_t) 方法


将 32 位整数值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(int32_t value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int32_t** | 要输出的值 |

## ConsoleOutput::Write(int64_t) 方法


将 64 位整数值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(int64_t value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int64_t** | 要输出的值 |

## ConsoleOutput::Write(float) 方法


将单精度浮点值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(float value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要输出的值 |

## ConsoleOutput::Write(const String\&) 方法


将指定的字符串对象输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(const String &value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要输出的字符串对象 |

## ConsoleOutput::Write(uint32_t) 方法


将无符号 32 位整数值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(uint32_t value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint32_t** | 要输出的值 |

## ConsoleOutput::Write(uint64_t) 方法


将无符号 64 位整数值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(uint64_t value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **uint64_t** | 要输出的值 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&) 方法


将指定字符数组的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 要输出的数组 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法


将指定字符数组中一段值的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 包含要输出值的数组 |
| index | **int32_t** | 输出范围起始的索引 |
| count | **int32_t** | 输出范围内元素的数量 |

## ConsoleOutput::Write(const char_t *) 方法


将指定的 C 字符串输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(const char_t *value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要输出的 C 字符串 |

## ConsoleOutput::Write(const TypeInfo\&) 方法


将指定 [TypeInfo](../../typeinfo/) 对象的字符串表示输出到当前对象表示的输出流。

```cpp
void System::ConsoleOutput::Write(const TypeInfo &value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 要输出的 [TypeInfo](../../typeinfo/) 对象 |

## ConsoleOutput::Write(const char *) 方法




```cpp
void System::ConsoleOutput::Write(const char *)=delete
```

## 另请参阅

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* 类 [ConsoleOutput](../)
* 类 [Object](../../object/)
* 类 [Decimal](../../decimal/)
* 类 [String](../../string/)
* 类 [TypeInfo](../../typeinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)