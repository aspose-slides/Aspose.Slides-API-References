---
title: ImportNode()
second_title: Aspose.Slides for C++ API 参考
description: 将节点从另一个文档导入到当前文档。
type: docs
weight: 469
url: /zh/system.xml/xmldocument/importnode/
---
## XmlDocument::ImportNode(SharedPtr\<XmlNode\>, bool) 方法


将节点从另一个文档导入到当前文档。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ImportNode(SharedPtr<XmlNode> node, bool deep)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 被导入的节点。 |
| deep | **bool** | **true** 表示执行深度克隆；否则为 **false**。 |

### 返回值

导入的[XmlNode](../../xmlnode/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)