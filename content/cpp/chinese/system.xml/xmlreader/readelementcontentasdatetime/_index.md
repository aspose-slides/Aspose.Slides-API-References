---
title: ReadElementContentAsDateTime()
second_title: Aspose.Slides for C++ API 参考
description: 读取当前元素并将内容作为 DateTime 对象返回。
type: docs
weight: 495
url: /zh/system.xml/xmlreader/readelementcontentasdatetime/
---
## XmlReader::ReadElementContentAsDateTime() 方法

读取当前元素并将内容作为 [DateTime](../../../system/datetime/) 对象返回。

```cpp
virtual DateTime System::Xml::XmlReader::ReadElementContentAsDateTime()
```

### 返回值

元素内容作为 [DateTime](../../../system/datetime/) 对象。

## XmlReader::ReadElementContentAsDateTime(String, String) 方法

检查指定的本地名称和命名空间 URI 是否与当前元素匹配，然后读取当前元素并将内容作为 [DateTime](../../../system/datetime/) 对象返回。

```cpp
virtual DateTime System::Xml::XmlReader::ReadElementContentAsDateTime(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空间 URI。 |

### 返回值

元素内容作为 [DateTime](../../../system/datetime/) 对象。

## 另见

* 类 [DateTime](../../../system/datetime/)
* 类 [XmlReader](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)