---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 79
url: /zh/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) method

创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树； **false** 只克隆节点本身。对于显著空白节点，无论参数设置如何，克隆的节点始终包含数据值。 |

### 返回值

克隆的节点。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)