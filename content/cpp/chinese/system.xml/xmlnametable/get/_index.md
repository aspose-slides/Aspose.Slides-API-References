---
title: Get()
second_title: Aspose.Slides C++ API 参考
description: 当在派生类中被重写时，获取包含给定数组中指定字符范围相同字符的原子化字符串。
type: docs
weight: 1
url: /zh/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

当在派生类中被重写时，获取与给定数组中指定字符范围相同字符的原子化字符串。

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要查找的名称的字符数组。 |
| offset | **int32_t** | 数组中的零基索引，指定名称的第一个字符。 |
| length | **int32_t** | 名称中的字符数。 |

### 返回值

如果字符串尚未被原子化，则返回原子化字符串或 **nullptr**。如果 **length** 为零，则返回 [String::Empty](../../../system/string/empty/)。

## XmlNameTable::Get(const String\&) 方法

当在派生类中被重写时，获取与指定字符串具有相同值的原子化字符串。

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 要查找的名称。 |

### 返回值

如果字符串尚未被原子化，则返回原子化字符串或 **nullptr**。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [XmlNameTable](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)