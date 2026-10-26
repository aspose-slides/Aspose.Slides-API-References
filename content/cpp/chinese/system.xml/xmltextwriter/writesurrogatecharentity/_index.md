---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API 参考
description: 为代理字符对生成并写入代理字符实体。
type: docs
weight: 391
url: /zh/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) 方法


为代理字符对生成并写入代理字符实体。

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowChar | char16_t | 低位代理字符。它的值必须在 **0xDC00** 和 **0xDFFF** 之间。 |
| highChar | char16_t | 高位代理字符。它的值必须在 **0xD800** 和 **0xDBFF** 之间。 |

## 参见

* 类 [XmlTextWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)