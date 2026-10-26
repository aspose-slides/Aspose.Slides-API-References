---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 创建此节点的副本。实体节点无法被克隆。在 XmlEntity 对象上调用此方法会抛出异常。
type: docs
weight: 170
url: /zh/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) 方法


创建此节点的副本。实体节点无法被克隆。在 [XmlEntity](../) 对象上调用此方法会抛出异常。

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 以递归克隆指定节点下的子树；**false** 仅克隆节点本身。 |

### 返回值

一个来自调用该方法的 [XmlNode](../../xmlnode/) 的副本。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)