---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 XmlNodeChangedEventArgs 类的新实例。
type: docs
weight: 79
url: /zh/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor


初始化 [XmlNodeChangedEventArgs](../) 类的新实例。

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 生成此事件的 [XmlNode](../../xmlnode/)。 |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 生成此事件的 [XmlNode](../../xmlnode/) 的旧父 [XmlNode](../../xmlnode/)。 |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 生成此事件的 [XmlNode](../../xmlnode/) 的新父 [XmlNode](../../xmlnode/)。 |
| oldValue | const [String](../../../system/string/)\& | 生成此事件的 [XmlNode](../../xmlnode/) 的旧值。 |
| newValue | const [String](../../../system/string/)\& | 生成此事件的 [XmlNode](../../xmlnode/) 的新值。 |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction。 |

## 另见

* 枚举 [XmlNodeChangedAction](../../xmlnodechangedaction/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [String](../../../system/string/)
* 类 [XmlNodeChangedEventArgs](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)