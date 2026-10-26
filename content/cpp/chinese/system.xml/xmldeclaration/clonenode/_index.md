---
title: CloneNode()
second_title: Aspose.Slides C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 157
url: /zh/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) 方法

创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 仅克隆节点本身。因为 [XmlDeclaration](../) 节点没有子节点，克隆的节点始终包括数据值，无论参数设置如何。 |

### 返回值

克隆的节点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlDeclaration](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)