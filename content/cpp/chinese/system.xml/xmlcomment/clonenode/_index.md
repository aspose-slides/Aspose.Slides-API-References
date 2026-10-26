---
title: CloneNode()
second_title: Aspose.Slides for C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 40
url: /zh/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) 方法

创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 仅克隆节点本身。由于注释节点没有子节点，克隆的节点始终包含文本内容，不受参数设置的影响。 |

### 返回值

克隆的节点。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlComment](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)