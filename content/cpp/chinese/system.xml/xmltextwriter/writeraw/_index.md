---
title: WriteRaw()
second_title: Aspose.Slides C++ API 参考
description: 从字符缓冲区手动写入原始标记。
type: docs
weight: 417
url: /zh/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

从字符缓冲区手动写入原始标记。

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 包含待写入文本的字符数组。 |
| index | **int32_t** | 缓冲区中指示待写入文本起始位置的索引。 |
| count | **int32_t** | 要写入的字符数。 |

## XmlTextWriter::WriteRaw(const String\&) 方法

从字符串手动写入原始标记。

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) 包含待写入的文本。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlTextWriter](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)