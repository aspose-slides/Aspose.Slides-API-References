---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 对指定的字符串进行原子化并将其添加到 NameTable。
type: docs
weight: 14
url: /zh/system.xml/nametable/add/
---
## NameTable::Add(const String\&) 方法


对指定字符串进行原子化并将其添加到 [NameTable](../)。

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | 要添加的字符串。 |

### 返回值

原子化后的字符串，或如果该字符串已存在于 [NameTable](../) 则返回已有的字符串。

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法


对指定字符串进行原子化并将其添加到 [NameTable](../)。

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要添加的字符串的字符数组。 |
| start | **int32_t** | 指定字符串第一个字符的零基索引。 |
| len | **int32_t** | 字符串中的字符数。 |

### 返回值

原子化后的字符串，或如果该字符串已存在于 [NameTable](../) 则返回已有的字符串。如果 **len** 为零，返回 [String::Empty](../../../system/string/empty/)。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [NameTable](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)