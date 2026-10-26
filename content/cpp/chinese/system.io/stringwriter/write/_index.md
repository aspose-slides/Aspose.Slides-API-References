---
title: Write()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的字符写入流。
type: docs
weight: 40
url: /zh/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) 方法

将指定的字符写入流。

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char_t | 要写入的值 |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 方法

将指定字符数组中指定的字符子范围写入流。

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 包含要写入字符的数组 |
| index | **int32_t** | 在 **buffer** 中子范围写入开始位置的基于 0 的索引 |
| count | **int32_t** | 要写入的子范围中的字符数 |

## StringWriter::Write(const String\&) 方法

将指定的字符串写入流。

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要写入的字符串 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [StringWriter](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)