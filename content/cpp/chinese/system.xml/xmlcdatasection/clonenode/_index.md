---
title: CloneNode()
second_title: Aspose.Slides 的 C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 53
url: /zh/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) 方法

创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 仅克隆节点本身。由于 CDATA 节点没有子节点，无论参数设置如何，克隆的节点始终会包含数据内容。 |

### 返回值

克隆的节点。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlCDataSection](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)