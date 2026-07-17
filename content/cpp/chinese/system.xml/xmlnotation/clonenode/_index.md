---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 创建此节点的副本。标记节点不能被克隆。在 XmlNotation 对象上调用此方法会抛出异常。
type: docs
weight: 118
url: /zh/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) 方法

创建此节点的副本。标记节点不能被克隆。在 [XmlNotation](../) 对象上调用此方法会抛出异常。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 只克隆节点本身。 |

### 返回值

一个从调用该方法的节点复制的 [XmlNode](../../xmlnode/) 副本。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlNotation](../)
* 名称空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)