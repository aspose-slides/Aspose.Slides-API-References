---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，将指定的字符串进行原子化并将其添加到 XmlNameTable。
type: docs
weight: 14
url: /zh/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法


在派生类中重写时，将指定的字符串进行原子化并将其添加到 [XmlNameTable](../)。

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要添加的名称的字符数组。 |
| offset | **int32_t** | 数组的零基索引，指定名称的第一个字符。 |
| length | **int32_t** | 名称中的字符数。 |

### 返回值

如果不存在，则返回新原子化的字符串；如果已存在，则返回已有的字符串。如果长度为零，则返回 [String::Empty](../../../system/string/empty/)。

## XmlNameTable::Add(const String\&) 方法


在派生类中重写时，将指定的字符串进行原子化并将其添加到 [XmlNameTable](../)。

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 要添加的名称。 |

### 返回值

如果不存在，则返回新原子化的字符串；如果已存在，则返回已有的字符串。

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [XmlNameTable](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)