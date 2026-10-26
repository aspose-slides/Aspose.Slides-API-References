---
title: WriteRaw()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，从字符缓冲区手动写入原始标记。
type: docs
weight: 287
url: /zh/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

在派生类中重写时，从字符缓冲区手动写入原始标记。

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 包含要写入文本的字符数组。 |
| index | **int32_t** | 缓冲区中指示要写入文本起始位置的索引。 |
| count | **int32_t** | 要写入的字符数。 |

## XmlWriter::WriteRaw(const String\&) 方法

在派生类中重写时，从字符串手动写入原始标记。

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) 包含要写入的文本。 |

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlWriter](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)