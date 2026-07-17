---
title: WriteLine()
second_title: Aspose.Slides for C++ API 参考
description: 将换行终止符写入流。
type: docs
weight: 92
url: /zh/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() 方法

将换行终止符写入流。

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) 方法

将指定的字符串以及随后的换行终止符写入流。

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要写入的字符串 |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) 方法


将指定对象的字符串表示以及随后的换行终止符写入流。

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要写入的对象 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) 方法


将指定数组中的所有字符以及随后的换行终止符写入流。

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要写入字符的数组 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法


将指定字符数组中指定的 UTF-16 子范围以及随后的换行终止符写入流。

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要写入字符的数组 |
| index | **int32_t** | 在 **buffer** 中子范围开始写入的 0 基索引 |
| count | **int32_t** | 要写入的子范围中的字符数；-1 表示子范围在 **buffer** 数组结束处终止 |

## StreamWriter::WriteLine(const char_t *) 方法


将指定的 C 字符串以及随后的换行终止符写入流。

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const char_t * | 要写入的 C 字符串 |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) 方法


将指定对象的字符串表示以及随后的换行终止符写入流。

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | 要写入的对象 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [StreamWriter](../)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)