---
title: CloneNode()
second_title: Aspose.Slides C++ API 参考
description: 创建此节点的副本。
type: docs
weight: 261
url: /zh/system.xml/xmldocument/clonenode/
---
## XmlDocument::CloneNode(bool) 方法


创建此节点的副本。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocument::CloneNode(bool deep) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | **bool** | **true** 递归克隆指定节点下的子树；**false** 仅克隆节点本身。 |

### 返回值

克隆的 [XmlDocument](../) 节点。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)