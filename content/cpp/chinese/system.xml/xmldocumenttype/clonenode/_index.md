---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 118
url: /zh/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) 方法

创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 表示递归克隆指定节点下的子树；**false** 表示仅克隆该节点本身。对于文档类型节点，克隆的节点始终包括子树，无论参数设置如何。 |

### 返回值

克隆的节点。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlDocumentType](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)