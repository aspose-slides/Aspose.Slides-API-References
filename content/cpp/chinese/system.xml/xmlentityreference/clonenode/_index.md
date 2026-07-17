---
title: CloneNode()
second_title: Aspose.Slides C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 92
url: /zh/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) 方法


创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 仅克隆节点本身。对于 [XmlEntityReference](../) 节点，此方法始终返回没有子节点的实体引用节点。替换文本在节点插入父节点时设置。 |

### 返回值

克隆的节点。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlEntityReference](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)