---
title: ReadToFollowing()
second_title: Aspose.Slides C++ API 参考
description: 读取，直到找到具有指定限定名称的元素。
type: docs
weight: 898
url: /zh/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) 方法

读取直到找到具有指定限定名称的元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 元素的限定名称。 |

### 返回值

**true** 如果找到匹配的元素；否则为 **false**，并且 [XmlReader](../) 处于文件结束状态。

## XmlReader::ReadToFollowing(String, String) 方法

读取直到找到具有指定本地名称和命名空间 URI 的元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空间 URI。 |

### 返回值

**true** 如果找到匹配的元素；否则为 **false**，并且 [XmlReader](../) 处于文件结束状态。

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)