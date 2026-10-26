---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被重写时，生成并写入代理字符对的代理字符实体。
type: docs
weight: 261
url: /zh/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) 方法


当在派生类中被重写时，生成并写入代理字符对的代理字符实体。

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lowChar | char16_t | 低位代理字符。其值必须在 0xDC00 到 0xDFFF 之间。 |
| highChar | char16_t | 高位代理字符。其值必须在 0xD800 到 0xDBFF 之间。 |

## 另见

* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)