---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字符写入流。
type: docs
weight: 79
url: /zh/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) 方法

将指定字符写入流。

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要写入的字符 |

## StreamWriter::Write(const String\&) 方法

将指定字符串写入流。

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要写入的字符串 |

## StreamWriter::Write(const SharedPtr\<Object\>\&) 方法

将指定对象的字符串表示写入流。

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要写入的对象 |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) 方法

将指定数组中的所有字符写入流。

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要写入字符的数组 |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

将指定字符数组中的子范围 UTF-16 字符写入流。

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要写入字符的数组 |
| index | **int32_t** | **buffer** 中子范围开始位置的 0 基索引 |
| count | **int32_t** | 要写入的子范围字符数；-1 表示子范围一直到 **buffer** 数组结束 |

## StreamWriter::Write(const char_t *) 方法

将指定的 C 字符串写入流。

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const char_t * | 要写入的 C 字符串 |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) 方法

将指定对象的字符串表示写入流。

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | 要写入的对象 |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)