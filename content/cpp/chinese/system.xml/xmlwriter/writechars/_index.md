---
title: WriteChars()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被覆盖时，逐个缓冲区写入文本。
type: docs
weight: 274
url: /zh/system.xml/xmlwriter/writechars/
---
## XmlWriter::WriteChars(ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

When overridden in a derived class, writes text one buffer at a time.

```cpp
virtual void System::Xml::XmlWriter::WriteChars(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 包含要写入文本的字符数组。 |
| index | **int32_t** | 缓冲区中指示要写入文本开始位置的索引。 |
| count | **int32_t** | 要写入的字符数。 |

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)