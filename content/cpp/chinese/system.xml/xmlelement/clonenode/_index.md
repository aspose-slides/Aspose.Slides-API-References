---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 196
url: /zh/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) 方法


创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树； **false** 仅克隆节点本身（如果该节点是 [XmlElement](../)，则克隆其属性）。 |

### 返回值

克隆的节点。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)