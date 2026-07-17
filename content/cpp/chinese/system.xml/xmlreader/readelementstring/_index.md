---
title: ReadElementString()
second_title: Aspose.Slides C++ API 参考
description: "读取仅包含文本的元素。但建议使用 XmlReader::ReadElementContentAsString 方法，因为它提供了更直接的方式来处理此操作。"
type: docs
weight: 859
url: /zh/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() 方法

读取仅包含文本的元素。但建议使用 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 方法，因为它提供了一种更直接的方式来处理此操作。

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### 返回值

读取的元素中包含的文本。如果元素为空，则返回空字符串。

## XmlReader::ReadElementString(String) 方法

在读取仅包含文本的元素之前，检查找到的元素的 [XmlReader::get_Name](../get_name/) 值是否与给定字符串匹配。但建议使用 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 方法，因为它提供了一种更直接的方式来处理此操作。

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要检查的名称。 |

### 返回值

读取的元素中包含的文本。如果元素为空，则返回空字符串。

## XmlReader::ReadElementString(String, String) 方法

在读取仅包含文本的元素之前，检查找到的元素的 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值是否与给定字符串匹配。但建议使用 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 方法，因为它提供了一种更直接的方式来处理此操作。

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 要检查的本地名称。 |
| ns | [String](../../../system/string/) | 要检查的命名空间 URI。 |

### 返回值

读取的元素中包含的文本。如果元素为空，则返回空字符串。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)