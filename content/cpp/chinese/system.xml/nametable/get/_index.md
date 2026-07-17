---
title: Get()
second_title: Aspose.Slides C++ API 参考
description: 返回具有指定值的原子化字符串。
type: docs
weight: 27
url: /zh/system.xml/nametable/get/
---
## NameTable::Get(const String\&) 方法

返回具有指定值的原子化字符串。

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 要查找的名称。 |

### 返回值

原子化字符串对象，如果字符串尚未原子化，则返回 **nullptr**。

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) 方法

返回包含给定数组中指定字符范围的相同字符的原子化字符串。

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 包含要查找名称的字符数组。 |
| start | **int32_t** | 指定名称第一个字符的基于零的数组索引。 |
| len | **int32_t** | 名称中的字符数。 |

### 返回值

原子化字符串，如果字符串尚未原子化，则返回 **nullptr**。如果 **len** 为零，则返回 [String::Empty](../../../system/string/empty/)。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [NameTable](../)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)